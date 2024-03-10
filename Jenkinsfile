pipeline {
    agent any
    
    environment {
        PATH = "$PATH:/usr/local/go/bin"
    }
        
        
        stage('Build') {
            steps {
               sh 'go build'
            }
        }
        
        stage('Test') {
            steps {
                sh 'go test'
            }
        }
    }
}
