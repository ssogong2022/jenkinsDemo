import java.text.SimpleDateFormat

pipeline {
    agent any

    stages {
        stage('Test') {
            steps{
                
                def dateFormat = new SimpleDateFormat("yyyyMMddHHmm")
                def date = new Date()
                
                def today = dateFormat.format(date) 
                bat "echo ${today}"
            }
        }
    }
}
