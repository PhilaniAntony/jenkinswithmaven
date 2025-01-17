node{
  stage('SCM Checkout'){
    git branch: 'main', url: 'https://github.com/PhilaniAntony/jenkinswithmaven'
  }
  stage('Compile-Package'){
    sh '/usr/local/opt/maven package'
  }
}
