node('built-in') 
{
    stage('Continuous Download_child') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_child') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
