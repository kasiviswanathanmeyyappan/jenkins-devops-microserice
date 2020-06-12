 pipeline {
 
    agent any


	environment{


		mavenHome = tool 'myMaven'
		PATH= "C:\Users\Home\Downloads\apache-maven-3.6.3-bin\apache-maven-3.6.3"
	}


	

	stages {

	stage('Build'){
	 
	   steps {	           
		     
				echo "Build"
			  }
	}

	stage('Version'){

		steps{

			sh "mvn --version"
		}
	}

   }
 
 }
