pipeline {
    agent any 
    stages {
        stage("build-stage") {
            steps {
                sh "mvn compile"
            }
        }
        stage("Test-stage") {
            steps {
                sh "mvn test"
            }
        }
    }
    
}
