pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from GitHub
                git 'https://github.com/riot020/date-time.git'
		git branch: 'main', url: 'https://github.com/riot020/date-time.git'
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
