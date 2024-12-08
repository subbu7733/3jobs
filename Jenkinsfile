
pipeline {
    agent any
    stages{
        stage('Git access'){
            steps{
                git branch : 'main' ,url :'https://github.com/subbu7733/3jobs.git'
            }
        }

        stage('Java execution'){
            steps{
                bat 'javac hello.java'
                bat 'java hello'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python hello.py'
            }
        }
    }
}
