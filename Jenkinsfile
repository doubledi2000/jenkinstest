pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/doubledi2000/jenkinstest.git'
            }
        }
    }
}