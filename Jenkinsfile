pipeline {
    agent any
    
    stages{
        stage('GIT Checkout')
        {
            steps{
              git branch: 'main', url: 'https://github.com/amartyakumar17/javacicode_UPES.git'
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