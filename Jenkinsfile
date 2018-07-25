pipeline {
    /* insert Declarative Pipeline here */
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
         }
         stage('What is the date') {
            steps {
		sh 'date'
	    }
         } 
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}

