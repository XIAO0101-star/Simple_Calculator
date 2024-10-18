pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        deleteDir() // Optional: Clear workspace
        git branch: 'main', url:
'https://github.com/YOUR-USERNAME/YOUR-REPO.git'
      }
    }

  stages {
    stage('Build') {
      steps {
        // Build steps here
      }
    }
    stage('Test') {
      steps {
        // Test steps here
      }
    }
    stage('Deploy') {
      steps {
        // Deploy steps here
      }
    }
  }
}
