pipeline {
    agent none
    stages{
		
	    stage('Checkout') { 
		   agent { 
		label 'Dev'
			} 
		steps{
			git 'https://github.com/sivaramsomala/CodeBase.git'
			
			}    
		steps{
			  sh '''cd /var/www/html
            	 sudo cp -r /home/ubuntu/jenkins/workspace/First_Declarative_Pipeline/* .'''
			    }
		    
		    
				
		}
	}
} 
