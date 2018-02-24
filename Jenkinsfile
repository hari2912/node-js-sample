pipeline {
    agent {
        label 'Nodejs_slave1'
    }
    stages {
        stage('test & start') {
            steps {
                sh 'cd /home/jenkins/workspace/nodejs_proj1'
                sh 'npm install'
                sh 'npm start'
            }
        }
    }
}
