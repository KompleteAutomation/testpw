pipeline {
    agent any

    stages {
         stage('Checkout external proj') {
			steps {
            git branch: 'main',
            sh "ls -lat"
        }
    }
         stage('clone') {
             steps {
                echo 'Clean'
               
            } 
             
         }
    }
}