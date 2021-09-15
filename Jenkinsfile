pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
		stage('Repo fetch') {
            steps {
                echo 'Feching
				bat "mkdir server"
				bat "cd server"
				git 'https://github.com/UtCode/Microservice-Projects.git'	
            }
        }
    }
}