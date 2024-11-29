pipeline {

	agent any

	stages {
		stage('Stage 1 - Checkout Code') {
			steps {					
				echo "Stage1"
			}
		}
		stage('Stage 2 - Compile Code') {
			steps {
				echo "Stage2"
			}
		}
		stage('Stage 3 - Run Unit Tests') {
			steps {
				echo "Stage3"
			}
		}

	}
	post{
		succes {
				echo "Complete"
		 }
	}
}
