pipeline {
    agent {
        label "java_nod"
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/learnasws16161616/maven.git'
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
