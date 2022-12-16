node{
  stage('SCM Checkout'){
  git 'https://github.com/meethatrik/sample-web-application'
  } 
  stage( 'Compile-Packages'){
    def mvnhome= tool name: 'maven-3', type: 'maven'
    sh "${mvnhome}/ubuntu/mvn package"
  }
}
