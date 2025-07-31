pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }  
         	    } 
            stage("maven_build") {
                steps {
                    sh "clean package"
                }
            }   
        }
}
