pipeline {
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

