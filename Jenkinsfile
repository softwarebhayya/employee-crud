node {
  stage('Clone repo'){
    checkout scm
  }
  
  stage('Check dependencies'){
      sh "java -version"
      sh "mvn -v"
      sh "docker info"
  }
}
