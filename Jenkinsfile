pipeline {
  agent any
  stages {
    stage('git the repo') {
      steps {
        git(url: 'https://github.com/shinobi94/demo_repo', branch: 'main')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}