pipeline { 
     agent any
     tools { 
      maven "maven-3.6.3" 
      jdk "jdk-11"
     }
     stages { 
     stage('Clean') { 
     steps {
              sh 'mvn clean' 
              } 
       }  
        
        stage('Test') {
        steps { 
            sh 'mvn test' 
               }                   
                       } 
         stage(' Package') { 
         steps { 
         sh 'mvn package' 
                } 
          }
          }
          }
