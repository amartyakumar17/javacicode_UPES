pipeline {
    agent any
    
    stages{
        stage('GIT Checkout')
        {
            steps{
              git branch: 'main', url: 'https://github.com/PariharAditya/javacicode_UPES.git'
            }
        }

        stage('UNIT TESTING')
        {
            steps{
              sh 'mvn test'
            }
        }
    }
}