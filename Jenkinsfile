pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "muie jenkins"'
        sh 'pwd'
        sh 'ls -l'
     //   sh 'scp index.html academy@192.168.56.6:/home/academy'
      }
    }

  }
  environment {
    CI = 'true'
  }
}
