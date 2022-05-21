pipeline {
withCredentials([sshUserPrivateKey(credentialsId: 'ssh_key', keyFileVariable: 'ssh_key')]) 
	{
agent any
	stages {
	stage{
		steps {
			echo 'Scanning the code'
		}
	}
	stage{
		steps{
		java -version
		mvn --version 
		}
	}
	stage{'deploy'}
	}
}
}
