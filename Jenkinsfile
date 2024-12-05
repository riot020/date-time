pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from GitHub
                git 'https://github.com/username/date-time.git'
            }
        }
        stage('Run Shell Script') {
            steps {
                // Run the shell script to display date and time
                sh './date-time.sh'
            }
        }
    }
}
