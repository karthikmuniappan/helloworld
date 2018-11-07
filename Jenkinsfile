#!groovy



node('jenkins-slave') {



	stage('SCM checkout') {

		checkout scm

	}



        stage('Build Docker image') {

	        sh 'docker build -t gcc:${BUILD_NUMBER} -f Dockerfile .'

        }

}