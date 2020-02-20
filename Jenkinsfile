// Jenkinsfile( Declarative Pipeline )
pipeline {
    agent any
    
    stages {
        stage('Build'){
            steps {
                echo "building..."
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
            }
        }
        stage('Test'){
            steps {
                echo "Testing..."
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying..."
            }
        }
    }
}
