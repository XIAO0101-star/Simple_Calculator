pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        deleteDir() // Optional: Clear workspace
        git branch: 'main', url:
'https://github.com/XIAO0101-star/Simple_Calculator.git'
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
