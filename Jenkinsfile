pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				git credentialsId: 'MYGit_Crdentials', url: 'https://github.com/sivaramsomala/CodeBase.git'
				sh cd /var/www/html
				sh sudo cp -r /home/ubuntu/jenkins/workspace/Build/* .
			}
				
		}
	}
}
