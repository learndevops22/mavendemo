pipeline {
    agent {
        label "java_node"
    }
    stages {
        stage('Checkout') {
            steps {
                echo "bulid id value is ${BUILD_ID}"
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
    
  
        
     
