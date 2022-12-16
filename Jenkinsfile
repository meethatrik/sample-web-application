node{
  stage('SCM Checkout'){
  git 'https://github.com/meethatrik/sample-web-application'
  } 
  stage( 'Compile-Packages'){
  sh 'mvn package'
  }
}
