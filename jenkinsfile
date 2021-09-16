pipeline {
    agent any 
    
    stages {
        stage ('Building') {
            steps { 
                echo 'the code will be now built into artifact'
        }
    }
    stage ('Artifact Archiving') {
            steps {
                echo 'the artifact will be archived to an artifact repository'
            }                
    }
    
    stage ('Testing') {
            steps { 
                echo 'the code will be tested'
        }
    }
    stage ('staging') {
            steps { 
                echo 'the code will be staged onto the staging server'
        }
    }

    stage ('deploy') {
            steps { 
                echo 'the code will be deployed'
        }
    }  
    }
}   
