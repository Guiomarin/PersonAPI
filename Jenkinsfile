pipeline {
  agent any
  stages {
    stage('Clean workspace') {
      steps {
        cleanWs()
      }
    }

    stage('Restore GIT') {
      steps {
        git(url: 'https://github.com/Guiomarin/PersonAPI.git', branch: 'main', credentialsId: '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')
      }
    }

  }
}