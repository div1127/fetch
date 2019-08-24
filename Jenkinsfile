pipeline {
   agent {label 'EWA DEPLOYMENT SERVER'}    
     environment {
       
       NVM_DIR="$HOME/.nvm"
   }
	stages {
		stage('Fetching tags') {
			steps {
        		checkout scm
    }
		}		
}
}
