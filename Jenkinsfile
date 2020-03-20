pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'Echo "Hello world"'
        build 'Test1'
      }
    }

    stage('Deploy') {
      steps {
        bat 'Echo "Deploy"'
      }
    }

    stage('Test') {
      steps {
        bat 'echo "Test"'
      }
    }

  }
}