import java.text.SimpleDateFormat

pipeline {
    agent {
        label "demoAgent"
    }
    
    stages {
        stage('Build') {
            steps {
                script {
                    def dateFormat = new SimpleDateFormat("yyyyMMddkkmm")
                    def date = new Date()
                    today = dateFormat.format(date)
                }                
                echo today
            }
        }
    }
}
