pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'git@github.com:IngSchick/jenkins-master.git', branch: 'main')
      }
    }

    stage('Build') {
      steps {
        echo 'Hello'
      }
    }

  }
}