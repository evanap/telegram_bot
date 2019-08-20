pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/evanap/telegram_bot', branch: 'develop', changelog: true, credentialsId: 'jenkins')
      }
    }
  }
}