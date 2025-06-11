pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git(branch: 'main', url: 'https://github.com/mohitshrivastava2008/mohit-intz.git')
            }
        }
        stage('Run Batch Script') {
            steps {
                bat 'hello.bat'
            }
        }
    }
}

