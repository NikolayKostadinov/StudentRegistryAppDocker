pipeline {
	agent any
	stages {
		stage('Install NPM packages') {
			steps {
				bat 'npm install'
			}
		}
	stage('Run UI tests') {
			steps {
				bat 'npm run test'
			}
		}
	}
}
