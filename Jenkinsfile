pipeline {
	agent any
	stages{
   	    stage("SCM"){		
	   	 steps{
                	//Getting code from git
        		git branch: 'sprint1', url: 'https://github.com/Rahul9391/java-hello-world-with-maven.git'		
			} 
           	}
	    stage("build package"){
			steps{
                         	//building package
        			sh 'mvn clean package'
			}
		}	
	}	

}


