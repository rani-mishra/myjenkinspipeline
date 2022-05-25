pipeline {

agent any

stages {
	stage('SCM') {
		steps {
                                		echo "git pull my code1"
                                		echo "git pull my code2"
                    	}
	}
	stage('Deploy') {
		steps {
	           		echo "deploying my code1"
                               		echo "deploying my code2"
                    	}

	}
	stage('Test') {
		steps {
			echo "test my final webapp"
                                       }

	}
                    stage('Deploy to Production ') {
		steps {
			echo "deploy  my final webapp"
                                       }

	}

}

}