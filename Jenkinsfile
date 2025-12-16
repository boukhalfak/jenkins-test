pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Récupération du code depuis GitHub'
            }
        }

        stage('Test') {
            steps {
                sh 'sh test.sh'
            }
        }
    }
}
