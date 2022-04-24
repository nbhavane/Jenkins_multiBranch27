node('master')

{

stage('ContinuousDownload_loans') 
   
	 {
	
    git 'https://github.com/nagshaik/maven.git'
    
	}

stage('Continuousbuild_loans') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}
