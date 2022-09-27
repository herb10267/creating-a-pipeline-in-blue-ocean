pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh 'echo "step1"'
          }
        }

        stage('step1 a') {
          steps {
            sh 'echo "step1 a"'
          }
        }

        stage('step 1 b') {
          steps {
            sh 'echo "step1 b"'
          }
        }

        stage('step1 c') {
          steps {
            sh 'echo "step1 c"'
          }
        }

      }
    }

    stage('step2') {
      parallel {
        stage('step2') {
          steps {
            sh 'echo "step2"'
          }
        }

        stage('step2 a') {
          steps {
            sh 'echo "step2 a"'
          }
        }

      }
    }

  }
}