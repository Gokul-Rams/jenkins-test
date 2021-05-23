pipeline {
    agent any
    tool{
        jdk
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
