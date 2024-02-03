pipeline{
	agent any 
	
	stages{
		stage('build'){
			steps{
				sh ''' 
					echo "This is Build"
					java -version
					ls
					mvn clean test
				'''
			}
		}
	}
}