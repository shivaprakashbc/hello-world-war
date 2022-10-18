pipeline {
	agent any

	stages  {
	   stage('checkout') {
	      steps {
                      sh 'pwd'
		      sh 'rm -rf hello-world-war'
		      sh ' git clone https://github.com/shivaprakashbc/hello-world-war.git'
            	    }
                 }
           stage('Test') {
               steps {
                echo 'Testing..'
                    }
                 }
           stage('Deploy') {
               steps {
                echo 'Deploying....'
                     }
                }
          }
  }
