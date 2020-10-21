pipeline {
    agent { 
		label 'Dev'
	}
    stages{
	    stage('Checkout') { 
		    
		steps{
			git 'https://github.com/sivaramsomala/CodeBase.git'
			
			}
		stage('Build'){
		    
		steps{
			  sh '''cd /var/www/html
            	 sudo cp -r /home/ubuntu/jenkins/workspace/First_Declarative_Pipeline/* .'''
			    }
		    
		    }
				
		}
	}
