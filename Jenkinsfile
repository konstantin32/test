pipeline {
  agent any
  stages {
    stage('init') {
      parallel {
        stage('init') {
          steps {
            sh '''echo "Hello"
'''
            sh 'echo "world"'
          }
        }

        stage('2') {
          steps {
            sleep 5
          }
        }

      }
    }

  }
}