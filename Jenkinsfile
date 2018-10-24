node{
stage('Code Checkout from GITHUB'){
git credentialsId: 'Git-Creds', url: 'https://github.com/OracleDBA/Rahil_WebApp.git'
}
stage('Compile and Package Maven'){
sh 'mvn compile'
}
}
