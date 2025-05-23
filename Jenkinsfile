pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Tool: Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Tool: JUnit'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Tool: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Tool: OWASP ZAP'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Tool: AWS EC2'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Tool: Postman'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Tool: AWS EC2'
            }
        }        
    }
}
