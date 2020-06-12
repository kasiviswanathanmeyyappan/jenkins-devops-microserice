 pipeline {
 
    agent any

	stages {

	stage('Build'){
	 
	   steps {	           
		     
				echo "Build"
				echo "BUILD_TAG - $env.BUILD_TAG"
			  }
	}


	stag('Build Docker Image'){


         script{

			 steps{

			 "docker build -t 569736/currency-exchange-devops:$env.BUILD_TAG"

		    } 
		 }
 	 
      }
 
    }
 }
