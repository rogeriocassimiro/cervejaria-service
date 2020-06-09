node{
  stage('SCM Checkout'){
    git 'https://github.com/rogeriocassimiro/cervejaria-service'
  }
  stage('Compile-Package') {
    sh 'mvn clean install'
  }
}
