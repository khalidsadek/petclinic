pipeline {


agent any

    stages {
      
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic'
			}
        }
		stage('pwd com') {
            steps {
				sh "pwd"
				sh "cd .."
				sh "pwd"
			
			}
        }
    
		stage('mvnw') {
			steps {
				script{
					"./mvnw package"
				}
			}

        }
	
    }
}
