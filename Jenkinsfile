pipeline{

 agent any
 tools { maven 'mvn'}
    stages {
        stage('checkout code'){
            steps{
                sh 'echo "checkout code"'
            }
        }
	stage('build'){
	    steps{
	    	sh 'mvn clean package'
	    	sh 'printenv'
	   }


	}
    }
    post {
    	changed {
    		sh 'echo status is different from last time'
    	}
    	success {
    		sh 'echo the pipeline is success'
    	}
    	aborted {
    		sh 'echo the pipeline is aborted'
    	}
    }
}
