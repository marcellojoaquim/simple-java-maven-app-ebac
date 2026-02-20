pipeline {
    tools {
    maven 'Maven 3.9.10'
}
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}