pipeline {
  agent any	 
  stages {
    stage('print my file') {
	  steps {
		  sh 'ls'
    }	
    }
    stage('copy my file to dest') {
	   steps {
		  sh 'sudo cp index.html /var/www/html/'
    }	    
  }
}
}   
