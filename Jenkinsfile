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
							echo 'mvn clean'
					}
			}
	}
}