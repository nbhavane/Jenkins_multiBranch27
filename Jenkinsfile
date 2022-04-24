node('master')

{

stage('ContinuousDownload_master') 
   
	 {
	
    git 'https://github.com/nagshaik/maven.git'
    
	}

stage('Continuousbuild_master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}


