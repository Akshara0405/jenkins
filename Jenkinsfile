pipeline {
    agent any

    stages {
        stage('Pull From GitHub') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Akshara0405/jenkins.git'
            }
        }
    }
}
