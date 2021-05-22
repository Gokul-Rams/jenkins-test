pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bash '''
                    dir
                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
