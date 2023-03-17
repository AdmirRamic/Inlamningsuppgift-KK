pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                dir('C:/Users/Admir/.jenkins/workspace/Inlamningsuppgift_KK_main/Tests'){ 
                    bat 'python -m unittest'
                }
            }
        }
        stage('Clean Workspace'){
            steps {
                cleanWs()
            }
        }
    }
}
