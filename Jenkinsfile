pipeline {
    agent any
    environment {
        def timestamp = sh(script: timestamp='date +%Y%m%d%H%M')
    }
    stages {
        stage('Build') {
            steps {
                
                echo "$timestamp"
            }
        }
    }
}
