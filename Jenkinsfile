node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Nithya1085/MyWebAppProject.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
