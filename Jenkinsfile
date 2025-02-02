@Library("Shared") _
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                
                    hello()
            
            }
        }
         stage('Clone') {
            steps {
                clone("https://github.com/tanyadevops/Jenkins-shared-libraries.git","main")
    
            
            }
        }
    }
}
