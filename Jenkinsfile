node{
   stage('SCM Checkout'){
   git 'https://github.com/phemmmie/new-app'
   
   }
   stage('Compile-Package'){
    def mvnHome = tool name: 'maven-3', type: 'maven'
      sh "${mvnHome}/opt/apache-maven-3.5.3/bin package"
   
   }


}
