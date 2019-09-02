

pipeline {
	agent any
	stages {
		stage('Create blue kubernetes cluster') {
			steps {
				withAWS(region:'us-east-1', credentials:'aws-static') {
					sh '''
						aws --version
					'''
				}
			}
		}

		

		
	}
}