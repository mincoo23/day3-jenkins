pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/mincoo23/day3-jenkins', branch: 'master', poll: true)
        sh 'npm install'
        sh '''npm run clean
'''
        sh 'npm run build'
      }
    }

  }
  environment {
    name = 'day3-jenkins'
  }
}