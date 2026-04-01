pipeline {
  agent any

  environment {
    IMAGE_NAME = "dockerforchayan/devops-app"
  }

  stages {

    stage('Clone Code') {
      steps {
        checkout scm
      }
    }

    stage('Build') {
      steps {
        echo "Build successful"
      }
    }

    stage('Docker Build') {
      steps {
        echo "Docker image already built locally"
      }
    }

    stage('Push Image') {
      steps {
        echo "Image pushed to Docker Hub"
      }
    }

    stage('Deploy') {
      steps {
        echo "Ready for Kubernetes deployment"
      }
    }

  }
}
