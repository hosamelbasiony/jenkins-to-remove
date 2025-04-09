pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/hosamelbasiony/jenkins-to-remove.git', branch: 'main', changelog: true)
      }
    }

  }
}