node{
stage('Code Checkout from GITHUB'){
git credentialsId: 'Git-Creds', url: 'https://github.com/OracleDBA/Rahil_WebApp.git'
}
stage('Compile and Package Maven'){
  def MavenHome = tool name: 'Maven-3.5.4', type: 'maven'
  def MavenBinary = "${MavenHome}/bin/mvn"
  echo "${MavenHome}" 
  echo "${MavenBinary}"
  sh 'mvn compile'
}
}
