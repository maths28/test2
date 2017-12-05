pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				bat 'mvn clean package'
				bat 'mvn test'
				bat 'dir target'
			}
		}
	}
}