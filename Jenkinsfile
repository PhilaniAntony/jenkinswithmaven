node{
  stage('SCM Checkout'){
    git branch: 'main', url: 'https://github.com/PhilaniAntony/jenkinswithmaven'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven3.9.9', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
