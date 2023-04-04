pipeline {
    agent any
    
    stages {
        stage("Java Version") {
            steps {
                script {
                    java -version
                }
            }
        }
        
        stage("Git Version") {
            steps {
                script {
                    git --version
                }
            }
        }
    }
}
