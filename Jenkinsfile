pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello Build '
      }
    }
    stage('Test') {
      steps {
        echo 'Hello Test'
      }
    }
    stage('Browser Tests') {
      steps {
        parallel(
          "Browser Tests": {
            echo 'Hello Browser Tests'
            
          },
          "Run": {
            echo 'run'
            
          }
        )
      }
    }
    stage('Dev') {
      steps {
        echo 'Hello Dev'
      }
    }
    stage('Integration') {
      steps {
        echo 'Hello Integration'
      }
    }
    stage('QA') {
      steps {
        echo 'Hello QA'
      }
    }
    stage('Pilot') {
      steps {
        echo 'Hello Pilot'
      }
    }
    stage('Prod') {
      steps {
        echo 'Hello Prod'
      }
    }
  }
}