pipeline {  
    agent any  
    tools {
  maven 'Maven_3.9'
}
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }  
         	    } 
         	    stage("maven_build") {
         	        steps {
         	            sh "mvn clean package"
         	        }
         	    }
        }
}
