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
				git 'https://github.com/UtCode/Microservice-Projects.git'
				dir(currency-conversion-service){
					echo 'inside dir..'
					sh 'pwd'
				}
            }
        }
    }
}