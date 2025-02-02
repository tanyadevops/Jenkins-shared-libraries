@Library("Shared") _
pipeline {
    agent any

    stages {
stage('Hello') {
            steps {
      echo "Hello..this is shared library" 
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
