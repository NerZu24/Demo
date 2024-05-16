pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                        echo "Build"
                        echo "One"
                }
            }
        }
        stage('run') {
            steps {
                script {
                    echo "Test"
                }
            }
        }
           stage('Powershell') {
            steps {
                script {
                    sh "hostname"
                }
            }
        }
    }
}
