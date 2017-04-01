pipeline {
  agent any
  stages {
    stage('Copy assets') {
      steps {
        echo 'Deploying Simplewebsys.org website'
        sh 'rsync -avz * websys@simplewebsys.org:~'
      }
    }
  }
}