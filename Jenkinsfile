pipeline {
  agent any
  stages {
    stage('Static Code Analysis') {
      parallel {
        stage('Static Code Analysis') {
          steps {
            sh 'phpcpd'
            sh 'phploc'
            echo 'Very Good!'
          }
        }
        stage('Sub1- Static Code Anaylis') {
          steps {
            echo 'This is sub step'
          }
        }
      }
    }
    stage('My Second Step') {
      steps {
        echo 'This is my second step'
      }
    }
  }
}