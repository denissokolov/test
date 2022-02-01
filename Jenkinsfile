pipeline {
  agent any
  stages {
    stage('test 1') {
      parallel {
        stage('test 1') {
          steps {
            sh 'ls'
          }
        }

        stage('test 2') {
          steps {
            sh 'ls'
          }
        }

      }
    }

    stage('test3') {
      parallel {
        stage('test3') {
          steps {
            sh 'ls'
          }
        }

        stage('test 4') {
          steps {
            sh 'ls'
          }
        }

      }
    }

  }
}