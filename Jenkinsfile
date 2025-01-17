node{
  stage('SCM Checkout'){
    git 'https://github.com/PhilaniAntony/jenkinswithmaven'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
