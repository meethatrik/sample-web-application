node{
  stage('SCM Checkout'){
    git branch: 'test', url: 'https://github.com/meethatrik/sample-web-application.git'
  } 
  stage( 'Compile-Packages'){
    def mvnhome= tool name: 'maven-3', type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  }
}
