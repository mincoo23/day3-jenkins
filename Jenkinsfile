pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/mincoo23/day3-jenkins.git', branch: 'master')
        sh 'npm install'
      }
    }

    stage('build') {
      steps {
        sh 'npm run clean'
        sh 'npm run build'
      }
    }

  }
  tools {
    nodejs 'nodejs'
  }
}