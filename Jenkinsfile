pipeline {
    agent none
    stages{
	    stage('Build') { 
		    agent { 
		      	label 'Dev'
		    }
		steps{
			git credentialsId: 'MYGit_Crdentials', url: 'https://github.com/sivaramsomala/CodeBase.git'
			sh 'cd /var/www/html'
			sh 'sudo cp -r /home/ubuntu/jenkins/workspace/Build/* .'
			}
				
		}
	}
}
