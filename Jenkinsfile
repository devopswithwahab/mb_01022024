node('master') 
{
   stage('Continuous Download_feature') 
	{
    		git branch: 'main', url: 'https://github.com/devopswithwahab/maven.git'
	}
   stage('Continuous Build_feature') 
	{
    		sh 'mvn package'
	}
	stage('Continuous Deployment_feature') 
	{
           
	}
stage('Continuous Testing_feature') 
	{
	     
	}
stage('Continuous Delivery_feature') 
	{
	        input 'Waiting for Approval from DM'
	}
	
}
