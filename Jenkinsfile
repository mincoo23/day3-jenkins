pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/mincoo23/day3-jenkins.git', branch: 'master')
        sh '''npm config ls
npm run clean
npm run build'''
      }
    }

  }
  tools {
    nodejs 'nodejs'
  }
}