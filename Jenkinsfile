// Jenkinsfile( Declarative Pipeline )
pipeline {
    agent any
    
    stages {
        stage('Build'){
            steps {
                bat 'mvn build'
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
            }
        }
    }
}
