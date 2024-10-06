pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                echo 'pulling ...'
                checkout scm  // This will use the Git repository configured in Jenkins.
            }
        }
        stage('mvn') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
