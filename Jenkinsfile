pipeline {
	agent any
	tools {
		maven 'Maven'
		jdk 'JDK-8'
	}
	stages {
		stage('Build') {
			steps {
				echo 'Building...'
				sh 'mvn -B -DskipTests clean package -f technical-challenge/pom.xml'
			}
		}
	}
}