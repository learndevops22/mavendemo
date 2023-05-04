pipeline {
    agent {
        label "java_node"
    }
    stages {
        stage('Checkout') {
            steps {
                echo "bulid id value is ${BUILD_ID}"
                echo "bulid tag value is ${BUILD_TAG}"
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
    
  
        
     
