pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "Stage 1"'
          }
        }

        stage('Stage 2') {
          steps {
            echo 'Stage 2 Printed'
          }
        }

      }
    }

  }
}