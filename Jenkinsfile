pipeline {
    agent any 
    tools { 
        maven "mvn3" 
    }
    docker {
        sh "docker run hello-world"
    }
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
