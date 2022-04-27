pipeline { 
    agent any  
    stages { 
        stage('Testing') {
          steps {
            echo 'running Tests'
            bat 'python sexy.py'
          }
        }
        stage('Build') { 
            steps { 
               echo 'Building jar files...' 
               bat 'mvn package'
            }
        }
    }
}
