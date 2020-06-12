 pipeline {
 
    agent any

	stages {

	stage('Build'){
	 
	   steps {	           
		     
				echo "Build"
			  }
	}

	stage('Compile'){

		steps{

			sh "mvn clean compile"
		}
	}

   }
 
 }
