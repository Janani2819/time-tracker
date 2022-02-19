pipeline {
       agent any
	stages {
	     stage('Init') {
		   steps {
			 echo 'jenkins code pipeline session!'
		    }
	      }
 	      stage('Build') {
		    steps {
			   echo 'Building sample Maven project'
		     }
               }
		
	       stage('Deploy') {
 		     steps {
			    echo 'Deploying in staging area'
	             }
  		}
	       
		stage('Deploy in production') {
 		     steps {
			    echo 'Deploying in production area'
	             }
  		}
	  }
}	   
