pipeline{

 agent any
 options{
 	buildDiscarder(logRotator(numToKeepStr:'3'))
 }

    stages {
    	stage('test env') {
	    	steps{
	    		echo "Running ${env.BUILD_NUMBER} on ${env.JENKINS_URL}"
	    		echo "print ${env.BRANCH_NAME}"

	    	}
    	}
    }

}
