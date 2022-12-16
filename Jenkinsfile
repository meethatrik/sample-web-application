node{
  stage('SCM Checkout'){
    git branch: 'test', url: 'https://github.com/meethatrik/sample-web-application.git'
  } 
  stage('Compile-Packages'){
    def mvnHome= tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/ubuntu/apache-maven-3.8.6//bin/mvn package"
  }
}
