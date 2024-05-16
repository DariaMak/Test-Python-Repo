pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch:'main' ,url: 'https://github.com/DariaMak/Test-Python-Repo.git'
                sh 'python3 file.py'
                
            }
        }
    }
}
