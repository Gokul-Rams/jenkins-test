pipeline {
    agent any
    tools{
        jdk jdk8
    }
    stages{
        stage('build'){
            steps{
                echo "building"
                sh "javac main.java"
                sh "java main" 
            }
        }
        stage('deploy'){
            steps{
                echo "deploy"
            }
        }
    }
}
