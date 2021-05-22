pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                cat samplefile
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
