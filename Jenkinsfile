import java.text.SimpleDateFormat

node {
  stage('test') {
    def dateFormat = new SimpleDateFormat("yyMMddHHmm")
    def date = new Date()
    def TODAY = dateFormat.format(date)
    
    sh "echo ${TODAY}"
  }
}
