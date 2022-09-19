pipeline {
  agent any
  stages {
    stage('Restore GIT') {
      steps {
        git(url: 'https://github.com/Guiomarin/PersonAPI.git', branch: 'master', credentialsId: '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')
      }
    }

  }
}