import java.text.SimpleDateFormat

pipeline {
    agent any

    stages {
        stage('Test') {
            steps{
                
                def dateFormat = new SimpleDateFormat("yyyyMMddHHmm")
                def date = new Date()
                
                today = dateFormat.format(date) 
            }
        }
    }
  post {
        always {
            echo today
        }
    }
}
