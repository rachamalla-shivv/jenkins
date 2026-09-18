pipeline {
    agent {
         node {
            label 'AGENT-01'
         }
    }    
    stages {
        stage('Build') {
            steps {
                echo "building"
            }
        }
        stage('Test') {
            steps {
                echo "testing"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying"
            }
        }
    }

}