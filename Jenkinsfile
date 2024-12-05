pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/riot020/date-time.git'
                git branch: 'main', url: 'https://github.com/riot020/date-time.git'
            }
        }
        stage('Run Script') {
            steps {
                sh './date-time.sh'
            }
        }
    }
}
