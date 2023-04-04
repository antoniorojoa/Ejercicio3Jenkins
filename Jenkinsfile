pipeline {
    agent any
    
    stages {
        stage("Java Version") {
            steps {
                script {
                    cmd "java -version"
                }
            }
        }
        
        stage("Git Version") {
            steps {
                script {
                    cmd "git --version"
                }
            }
        }
    }
}
