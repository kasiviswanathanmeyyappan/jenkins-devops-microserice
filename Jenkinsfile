 pipeline {
 
    agent any

	//agent { docker {image 'maven:3.6.3'} }

    environment {

		//dockerHome = tool 'myDocker'
		mavenHome= tool 'mymaven'
		PATH = "$mavenHome/bin:$PATH"
	}
	stages {

	stage('Build'){
	 
	   steps {		 
        
		 sh 'mvn --version'
		// sh 'docker version'

		echo "Build"
		echo "PATH - $PATH"
	  }
	}
	stage('Test') {

		steps{
		echo "Test"
	  }
	}

	stage('IntegrationTest'){

		steps{

		echo "IntegrationTest"
		}
	
	}

   }
 
 }
