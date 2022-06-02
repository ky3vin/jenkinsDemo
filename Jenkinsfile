pipeline {
    agent any
     environment {
        def TIMESTAMP = sh(script: "echo 'date +%Y%m%d%H%M'", returnStdout: true).trim()
    }
    stages {
        stage('Build') {
            steps {
                 echo "$TIMESTAMP"
            }
        }
    }
}
