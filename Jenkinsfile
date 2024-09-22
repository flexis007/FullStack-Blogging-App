pipeline {
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk18'
    }
  stage('Compile') {
            steps {
               sh "mvn compile"
            }
        }
        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        
        stage('package') {
            steps {
                sh "mvn package"
            }
        }
    }

