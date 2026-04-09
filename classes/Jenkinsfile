pipeline {
    agent any

    tools {
        maven 'Maven'   // Make sure Maven is configured in Jenkins
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/DeekshaHarish12/MyMavenApp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
