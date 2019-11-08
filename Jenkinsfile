pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "muie jenkins"'
        sh 'pwd'
        sh 'ls -l'
        sh 'scp index.html dreygos@192.168.56.6:/home/dreygos'
      }
    }

  }
  environment {
    CI = 'true'
  }
}
