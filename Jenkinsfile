properties([parameters([booleanParam(description: 'fdfgd', name: 'www')])])
pipeline {
    agent any

    stages {
        stage('Run_app') {
            steps {
                bat 'python main.py'
            }
        }
        stage('Test_app') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
