pipeline {
    agent {
        label 'lzx-package'  
    }
    environment {
        GIT_HTTP_VERSION = 'HTTP/1.1'
    }
    stages {
        stage('Build') { 
            steps {
                bat  'npm install' 
            }
        }
    }
}