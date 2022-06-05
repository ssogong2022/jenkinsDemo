import java.text.SimpleDateFormat

pipeline {
    agent any

    stages {
        stage('test') {
            def dateFormat = new SimpleDateFormat("yyyyMMddHHmm")
            def date = new Date()
                
            today = dateFormat.format(date) 
        }
    }
  post {
        always {
            echo today
        }
    }
}
