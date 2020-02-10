pipeline{

 agent any
 options{
 	retry(2)
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
			error('emm....')

		}
	}

	}

}
