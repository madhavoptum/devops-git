node {
stage('SCM Checkout'){
  
git 'https://github.com/madhavoptum/devops-git'
}
stage('compile Package'){
  def mvnHome = tool name: 'Maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
