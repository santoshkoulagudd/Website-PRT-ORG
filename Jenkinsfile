pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url:'https://github.com/santoshkoulagudd/Website-PRT-ORG.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
