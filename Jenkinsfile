pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/comranIT/Git-Jen-Py.git'
                bat 'python main.py'
            }
        }
    }
}
