pipeline{

 agent any
 tools{ maven 'mvn'}
    stages{
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
}
