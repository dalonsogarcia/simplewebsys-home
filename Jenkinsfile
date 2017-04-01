pipeline {
  agent any
  stages {
    stage('Copy assets') {
      steps {
        echo 'Deploying Simplewebsys.org website'
        sh 'rsync -avz images index.html scripts styles websys@simplewebsys.org:~/simplewebsys-home'
      }
    }
  }
}