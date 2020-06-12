 pipeline {
 
    agent any


	environment{

		mavenHome = tool 'myMaven'
		PATH= "$mavenHome/bin:$PATH"
	}


	

	stages {

	stage('Build'){
	 
	   steps {	           
		     
				echo "Build"
			  }
	}

	stage('Version'){

		steps{

			sh 'mvn --version'
		}
	}

   }
 
 }
