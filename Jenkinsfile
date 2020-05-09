pipeline{
	agent any
	tools {
  maven 'maven3'
        }

	stages{
 
  stage('mvn clean package'){
	   steps{
	 sh 'mvn clean package'
	}
 	}


  }
}
