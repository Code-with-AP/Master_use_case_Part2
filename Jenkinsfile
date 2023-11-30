pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                dir("Anshul_Prajapati_189619_Master_Use_case_Part2") {
		bat "mvn clean"
	}
            }
        }
        stage('Compile') {
            steps {
	dir("Anshul_Prajapati_189619_Master_Use_case_Part2") {
		bat "mvn compile"
	}
            }
        }
        stage('Test') {
            steps {
	dir("Anshul_Prajapati_189619_Master_Use_case_Part2") {
		bat "mvn test"
	}
            }
        }
        stage('Result') {
            steps {
                echo "Result"
            }
        }
    }
}
