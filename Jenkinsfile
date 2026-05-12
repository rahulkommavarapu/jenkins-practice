pipeline {
    agent {label 'AGENT'}
    environment {
        PROJECT = 'EXPENSE'
        COMPONENT = 'BACKEND'
    }
    options {
        disableConcurrentBuilds()
    }
    stages {
        stage('Build'){
            steps {
                script{
                sh '''
                    echo "Hello this is Build"
                 '''
                }
            }
        }
             stage('Test'){
            steps {
                script{
                sh '''
                    echo "Hello this is Test"
                 '''
                }
            }
        }
             stage('Deploy'){
            steps {
                script{
                sh '''
                    echo "Hello this is Deploy"
                 '''
                }
            }
        }
    }
    post {
         always {
               echo 'I Will Always  say hello again'
         }
         failure {
             echo 'I will run when Pipelie is Failed'
         }
         success {
             echo 'I will run when pipeline is success'
         }
    }
}