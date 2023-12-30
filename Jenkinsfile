#!groovy
pipeline {
    agent any

    stages {
        stage('publish junit file') {
            steps {
                script {
                  // withChecks('Junit') {
                    junit 'junit.xml'
                  // }
                }
            }
        }
    }
}
                  
