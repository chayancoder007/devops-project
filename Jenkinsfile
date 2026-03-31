pipeline {
  agent any

  stages {

    stage('Clone Code') {
      steps {
        checkout scm
      }
    }

    stage('Build App') {
      steps {
        echo "Building app..."
      }
    }

    stage('Test') {
      steps {
        echo "Running tests..."
      }
    }

    stage('Deploy') {
      steps {
        echo "Deploy stage (simulated)"
      }
    }
  }
}
