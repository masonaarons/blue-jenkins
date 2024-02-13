pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('testing') {
      parallel {
        stage('testing') {
          steps {
            echo 'Testing'
          }
        }

        stage('Parallel') {
          steps {
            echo 'parallel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'building'
      }
    }

    stage('Clean Up') {
      steps {
        echo 'Cleaning'
      }
    }

  }
}