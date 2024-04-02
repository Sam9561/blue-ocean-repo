pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
ls'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'ls'
          }
        }

        stage('testpara') {
          steps {
            echo 'i love you shyam'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy successfully'
      }
    }

  }
}