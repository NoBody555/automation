node {
  
 
   stage('SCM Checkout'){
    // Clone repo
	git branch: 'branch2', 
	credentialsId: 'github', 
	 url: 'https://github.com/NoBody555/automation'
   
   }
   
   stage('TestMvn'){
         def mvn =  tool name: 'Maven_Home', type: 'maven'
	   sh "${mvn}/bin/mvn test"
	 }
      
   }
