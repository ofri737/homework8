pipeline {
    agent any

    stages {
        stage('1') {
            steps {
                git branch: 'main', url: 'https://github.com/ofri737/homework8.git'
                bat 'python "method1.py"'
		bat 'python "method2.py"'
            }
        }
    }
}