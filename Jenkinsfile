pipeline {
  agent any

  environment {
    IMAGE_NAME = "admin/devops-app"
  }

  stages {

    stage('Clone Code') {
      steps {
        checkout scm
      }
    }

    stage('Build Docker Image') {
      steps {
        bat 'docker build -t %IMAGE_NAME% .'
      }
    }

  }
}
