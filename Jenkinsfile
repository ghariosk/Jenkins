#!/usr/bin/env groovy

node {
    stage("hello") {
        echo 'Hello World'
    } 

    stage("test2") {

        echo 'Hello Wolrd'
        echo 'Another hello test'

        println 'test2'

        git credentialsId: '001', url: 'git@github.com:ghariosk/Python.git'


        sh '''

        	ls -al

     	'''
    }
}

//a20565f22911f70291efc311ae3e740b9192063f
// vim : ft=groovy

