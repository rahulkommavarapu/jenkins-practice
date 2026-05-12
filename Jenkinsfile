pipeline {
    agent {label 'AGENT'}
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
}