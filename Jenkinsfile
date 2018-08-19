pipeline {
  agent any
  stages {
    stage('Static Code Analysis') {
      steps {
        sh 'phpcpd'
        sh 'phploc'
        echo 'Very Good!'
      }
    }
    stage('My Second Step') {
      steps {
        echo 'This is my second step'
      }
    }
  }
}