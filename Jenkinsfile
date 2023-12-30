#!groovy
pipeline {
    agent any

    stages {
        stage('hello') {
            steps {
                helloWorld 'Jean'
            }
        }
        
        stage('publish junit file') {
            steps {
                // script {
                  // withChecks('Junit') {
                    junit 'junit.xml'
                  // }
                //}
            }
        }
    }
}
                  
