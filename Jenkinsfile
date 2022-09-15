pipeline {
  agent any
  stages {
    stage('Pull') {
      steps {
        git(url: 'https://github.com/jorgegonzalezUTEC/jenkins.git', branch: 'main', credentialsId: 'jorgegonzalezUTEC')
      }
    }

  }
}