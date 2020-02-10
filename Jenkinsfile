pipeline{

 agent any
 options{
 	buildDiscarder(logRotator(numToKeepStr:'3'))
 }

    stages {
    	steps{
    		echo 'Running ${env.BUILD_NUMBER} on ${env.JENKINS_URL}'
    		echo 'print ${env.BRANCH_NAME}'
    		echo 'print ${env.BUILD_URL}'
    		echo 'print ${env.GIT_BRANCH}'
    	}
    }

}
