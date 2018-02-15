pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'test'
        junit(testResults: 'JunitResults', allowEmptyResults: true, healthScaleFactor: 1)
      }
    }
  }
  environment {
    Dev = 'Development'
  }
}