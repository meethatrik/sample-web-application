node{
  stage('SCM Checkout'){
    git branch: 'test', url: 'https://github.com/meethatrik/sample-web-application.git'
  } 
  stage('Compile-Packages'){
    def mvnHome= tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/usr/share/maven package"
  }
}
