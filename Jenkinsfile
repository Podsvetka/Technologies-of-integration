pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Building project..."'
        sh 'mkdir build'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "Running tests..."'
      }
    }
  }
}
