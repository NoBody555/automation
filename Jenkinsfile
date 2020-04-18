node {
  
 
   stage('SCM Checkout'){
    // Clone repo
	git branch: 'branch2', 
     url: 'https://github.com/NoBody555/automation'
   
   }
   
   stage('Compile-Test'){
          tool name: 'Maven_Home', type: 'maven'
	   sh 'mvn test'
	 }
      
   }
