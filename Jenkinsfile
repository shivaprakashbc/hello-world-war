pipeline {
	agent { label 'slave2' }

	stages  {
	   stage('checkout') {
	      steps {
                      sh 'pwd'
		      sh 'rm -rf hello-world-war'
		      sh ' git clone https://github.com/shivaprakashbc/hello-world-war.git'
            	    }
                 }
           stage('build') {
               steps {
                     sh 'ls'
		     sh 'cd hello-world-war'
		     sh 'mvn clean package'
                    }
                 }
           stage('Deploy') {
               steps {
                echo 'Deploying....'
                     }
                }
          }
  }
