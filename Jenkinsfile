pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo 'Building..'
                    cd
                    cat samplefile
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
