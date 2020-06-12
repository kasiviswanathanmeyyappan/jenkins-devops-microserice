 pipeline {
 
    agent any

	//agent { docker {image 'maven:3.6.3'} }

    environment {

		//dockerHome = tool 'myDocker'
		mavenHome = tool 'myMaven'
		PATH = "$mavenHome/bin:$PATH"
	}

	stages {

	stage('Build'){
	 
	   steps {	           
		     
				echo "Build"
			  }
	}
	
   }
 
 }
