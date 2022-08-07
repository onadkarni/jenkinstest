pipeline {
    agent any
    stages {
        stage("build") {
            steps {
              echo 'building the application... can you see'
            }
        }
        stage("test") {
            steps {
              echo 'testing the application ..... can you see me testing 1.2.3'
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying the application can you see me deploy?"
                    
                }
            }
        }
    }   
}
