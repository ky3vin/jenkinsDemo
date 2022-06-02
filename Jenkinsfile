import java.text.SimpleDateFormat

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    def dateFormat = new SimpleDateFormat("yyyyMMdd")
                    def date = new Date()
                    today = dateFormat.format(date)
                }                
                echo today
            }
        }
    }
}
