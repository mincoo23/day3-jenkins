pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/mincoo23/day3-jenkins', branch: 'master', poll: true)
      }
    }

    stage('stage2') {
      steps {
        build 'day3-job'
      }
    }

  }
  environment {
    name = 'day3-jenkins'
  }
}