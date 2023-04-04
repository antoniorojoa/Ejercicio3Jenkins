pipeline {
    agent any
    
    stages {
        stage("Java Version") {
            steps {
                script {
                    echo "Version de Java"
                    bat "java -version"
                }
            }
        }
        
        stage("Git Version") {
            steps {
                script {
                    echo "Version de Git"
                    bat "git --version"
                }
            }
        }
    }
}
