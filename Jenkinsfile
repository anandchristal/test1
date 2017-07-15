node {
  git url: 'https://github.com/anandchristal/test1.git'
  def mvnHome = tool 'M3'
  sh "${mvnHome}/bin/mvn -B"
  //sh "${mvnHome}/bin/mvn -B -Dmaven.test.failure.ignore verify"
  //step([$class: 'JUnitResultArchiver', testResults:
//'**/target/foobar/TEST-*.xml'])
}
