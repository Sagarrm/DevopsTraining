pipeline
{
	agent any
	tools
	{
		maven 'MAVEN_HOME'
	}
	
	stages{
			stage('Welcome Stage')
			{
					steps
					{
							echo 'Welcome to Jenkins Pipeline'
					}
			}
			stage('Clean Stage')
			{
					steps
					{
							echo 'executing mvn clean'
							sh 'mvn clean'
					}
			}
			stage('Install Stage')
			{
					steps
					{
							echo 'executing mvn install'
							sh 'mvn install'
					}
			}
	}
}