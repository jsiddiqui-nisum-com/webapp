pipeline {
  agent any 
  
  stages {
   stage('Build'){
     steps {
	   sh "${MAVEN_HOME}/bin/mvn clean package"
	 }
   }
   
   stage('Test')
   {
    steps{
	 echo 'Testing...;
	 
	}
   }
   
   stage('Deploy')
   {
    steps{
	 echo 'Deploy...;
	 
	}
   }
   
  }
}
