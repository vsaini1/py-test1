pipeline {
    agent any

    stages {
        stage('SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/vsaini1/py-test1.git'
            }
        }
        stage('Python Run') {
            steps {
                sh 'python test1.py'
            }
        }
    }
}
