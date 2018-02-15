pipeline {
  agent {
    docker {
      image 'mysql:5.7'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Krishna279/html.git', branch: 'master')
      }
    }
  }
}