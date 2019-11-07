pipeline {
    agent any
    
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "muie jenkins"'
                build job: 'day3-jenkins-2', wait: false
            }
        }
    }
}
