import java.text.SimpleDateFormat

node {
  stage('test') {
    def dateFormat = new SimpleDateFormat("yyMMddHHmm")
    def date = new Date()
    def TODAY = dateFormat.format(date)
    
    sh "echo ${TODAY}"
  }
}
출처: https://www.oofbird.me/75 [OOFBIRD.ME:티스토리]
