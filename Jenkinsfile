pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('Build') {
      steps {
        echo 'Building....'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing....'
          sh 'npm test'
      }
    }

  }
}
