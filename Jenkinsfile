pipeline {
    agent {
        label 'Nodejs_slave1'
    }
    stages {
        stage('test & start') {
            steps {
                sh 'npm install'
                sh 'npm start'
            }
        }
    }
}
