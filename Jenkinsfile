pipeline {
    agent any
    tools{
        jdk8
    }
    stages{
        stage('build'){
            steps{
                echo "building"
                javac main.java
                java main 
            }
        }
        stage('deploy'){
            steps{
                echo "deploy"
            }
        }
    }
}
