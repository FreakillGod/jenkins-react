pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/FreakillGod/jenkins-react.git', branch: 'main')
      }
    }

    stage('Log Files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}