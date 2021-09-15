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
                echo 'Feching..'
				bat "mkdir server"
				dir(server){
					git 'https://github.com/UtCode/Microservice-Projects.git'
				}					
            }
        }
    }
}