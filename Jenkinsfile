pipeline {
  agent any
  stages {
    stage('Run') {
      steps {
        git(url: 'https://github.com/PraveenSanjay/Demorepo.git', branch: 'new')
      }
    }
    stage('execute') {
      steps {
        echo 'Hello world'
      }
    }
  }
}