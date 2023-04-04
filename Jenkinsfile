pipeline {
    agent any
    
    stages {
        stage("Java Version") {
            steps {
                script {
                    echo "Versión de Java"
                    bat "java -version"
                }
            }
        }
        
        stage("Git Version") {
            steps {
                script {
                    echo "Versión de Git"
                    bat "git --version"
                }
            }
        }
    }
}
