pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Build"'
      }
    }
  }
  post {
    always {
      echo "This will run"
    }
    success {
      echo "This will run if successfull"
    }
    failure {
      echo "This will run if failure"
    }
    unstable {
      echo "This will run if unstable"
    }
    changed {
      echo "This will run if changed"
    }
  }
}
