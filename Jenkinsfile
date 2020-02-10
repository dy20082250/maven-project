pipeline{

 agent any
 options{
 	buildDiscarder(logRotator(numToKeepStr:'3'))
 }

    stages {

    stage('checkout code'){
        steps{
            sh 'echo "checkout code"'

            }
        }
	stage('build'){
	    steps{
	   //	sh 'mvn clean package'
	    	sh 'printenv'
	   }
	}
	stage('test'){
		steps{
			sh 'echo ok'
		}
	}

	}
	post {
		always{
			cleanWs()
		}
	}

}
