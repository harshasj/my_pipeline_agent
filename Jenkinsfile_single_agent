pipeline {
	agent {
		label 'agent1'
	}
	stages {
		stage('Build'){
			steps{
				sh  '''
						echo "This is a Build stage "
						sleep 2
					'''
			}
		}
		stage('Deploy'){
			steps{
				sh  '''
						echo "This is a Deploy stage "
						sleep 2
					'''
			}
		}
		stage('Test'){
			steps{
				sh  '''
						echo "This is a Test stage "
						sleep 2
					'''
			}
		}
	
	}


}