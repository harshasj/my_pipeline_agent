pipeline {
	agent none
	stages {
		stage('Build'){
			agent {
				label 'agent2'
			}
			steps{
				sh  '''
						echo "This is a Build stage "
						sleep 2
					'''
			}
		}
		stage('Deploy'){
			agent {
				label 'agent1'
			}
			steps{
				sh  '''
						echo "This is a Deploy stage "
						sleep 2
					'''
			}
		}
		stage('Test'){
			agent {
				label 'agent2'
			}
			steps{
				sh  '''
						echo "This is a Test stage "
						sleep 2
					'''
			}
		}
	
	}


}