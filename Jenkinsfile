pipeline {
	agent any
	    
	stages {
	stage ('Initialize') {
	steps {
	sh 
	 echo "PATH = ${PATH}"
	 echo "M2_HOME = ${M2_HOME}"
						mvn -f demo/pom.xml install
						
	  
	}
	}
	

	stage ('Build') {
	steps {
	echo 'This is a minimal pipeline.'
	}
	}
	}
	}
