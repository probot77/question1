pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/probot77/question1.git'
            }
        }
        stage('Run Shell Script') {
            steps {
		sh 'chmod +x displaytime.sh'
                sh './displaytime.sh'
            }
        }
    }
}
