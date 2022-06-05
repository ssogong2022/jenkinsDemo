import java.text.SimpleDateFormat

node {
  stage('test') {
    
    def dateFormat = new SimpleDateFormat("yyyyMMddHHmm")
    def date = new Date()
    def TODAY = dateFormat.format(date)

    bat "echo ${TODAY}"
  }
}
