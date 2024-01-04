node('master') 
{
   stage('Continuous Download_master') 
	{
    		git branch: 'main', url: 'https://github.com/devopswithwahab/maven.git'
	}
   stage('Continuous Build_master') 
	{
    		sh 'mvn package'
	}

	
}
