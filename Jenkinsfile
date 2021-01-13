node{
   stages {
          stage("Scm Checkout") {
            git "https://github.com/michaelonye/bootique"
          }
          
          stage('compile-package') {
           sh 'mvn package'
          }
          
       }   
