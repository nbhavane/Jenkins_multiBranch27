node('master')

{

stage('ContinuousDownload_loans') 
   
	 {
	
    git 'https://github.com/nagshaik/maven.git'
    
	}

stage('Continuousbuild_loans') 
   
	 {
	
   sh label: 'Slave_lab', script: 'mvn package'
	}
}
