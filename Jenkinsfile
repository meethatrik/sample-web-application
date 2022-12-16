node{
  stage('SCM Checkout'){
    git 'https://github.com/meethatrik/sample-web-application.git'
  } 
  stage( 'Compile-Packages'){
    def mvnhome= tool name: 'maven-3', type: 'maven'
    sh "${mvnhome}/user/bin/mvn package"
  }
}
