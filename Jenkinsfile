node{
stage('SCM Checkout'){  
git 'https://github.com/revathipriya-it21/jenkins'
}
stage('Compile-Pakage'){
    def mnvHome = tool name: 'MAVEN_HOME', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
  
}
