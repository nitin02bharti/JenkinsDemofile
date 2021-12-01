pipeline {
    agent none 
    
    stages {
      stage ("Build") {
            steps {
                echo "Building..."
            }
      } 
      stage ("Windows") {
          agent {
              label "windows"
          }
      }
      stage ("Test") {
          steps {
              echo "Testing..."
          }
      }
      stage ("Deploy") {
          steps {
              echo "Deploying..."
          }
      }
    }
}
