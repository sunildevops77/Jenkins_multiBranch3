node('master')

{

stage('Continuous Download_master') 
   
	 {
	
    git 'https://github.com/sunildevops77/maven.git'
    
	}

stage('Continuous build_master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}


}


