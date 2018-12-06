node{
   stage('SCM Checkout'){
     git 'https://github.com/AkibaSato/jenkins_test'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'MAVEN', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
}


