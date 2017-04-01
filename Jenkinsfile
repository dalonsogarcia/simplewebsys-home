pipeline {
  agent any
  stages {
    stage('Copy assets') {
      steps {
        sh 'rsync -avz * websys@simplewebsys.org:~'
      }
    }
  }
}