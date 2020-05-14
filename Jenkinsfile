node{
  stage('SCM Checkout'){
  git 'https://github.com/MayankGupta1217/Jenkins'
  }
    stage('Compile-Package')
  {
    def mvn = tool (name: 'maven1', type: 'maven') + '/bin/mvn'
   // def mvnHome = tool name: 'maven1', type: 'maven'
    //sh"${mvnHome}"
  }  
}
