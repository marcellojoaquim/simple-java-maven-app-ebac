pipeline {
    agent any
    tools {
        maven 'Maven 3.9.10'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -version'
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}