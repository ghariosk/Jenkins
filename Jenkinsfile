#!/usr/bin/env groovy


def asRoot(anything) {
	withCredentials([usernameColonPassword(credentialsId: '002', variable: 'MY_CREDENTIAL_ROOT')]) {
	 anything() 
	}
}




node {
    stage("hello") {
        echo 'Hello World'
    } 

    stage("test2") {

    	
    // some block



        echo 'Hello Wolrd'
        echo 'Another hello test'

        println 'test2'


        git credentialsId: '001', url: 'git@github.com:ghariosk/Python.git'

        asRoot{ 



	        sh '''

	        	ls -als
	        	echo "50" | python prime.py

	     	'''
	    }
     	

     	
    }
}

//a20565f22911f70291efc311ae3e740b9192063f
// vim : ft=groovy

