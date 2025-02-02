@Library("Shared") _
pipeline {
    agent any

    stages {
stage('Helllo') {
            steps {
      echo "Hello" 
    }
        }
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
