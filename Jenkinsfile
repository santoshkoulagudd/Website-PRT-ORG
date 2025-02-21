pipeline {
    agent none
    stages {
        stage('Clone Repository') {
            steps {
                git credentialsId: '9532af7f-38df-4494-9458-3c5311ead921', url:'https://github.com/santoshkoulagudd/Website-PRT-ORG.git'
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
