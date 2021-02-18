pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Build'
      }
    }

    stage('Dev') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Dev'
        sleep 30
      }
    }

    stage('Test') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Test'
        sleep 20
      }
    }

    stage('Prod') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Prod'
        sleep 30
      }
    }

  }
}