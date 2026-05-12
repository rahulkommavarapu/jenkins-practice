pipeline {
    agent {lable 'AGENT 1'}
    stages {
        stage('Build'){
            steps {
                scripts{
                sh '''
                    echo "Hello this is Build"
                 '''
                }
            }
        }
             stage('Test'){
            steps {
                scripts{
                sh '''
                    echo "Hello this is Test"
                 '''
                }
            }
        }
             stage('Deploy'){
            steps {
                scripts{
                sh '''
                    echo "Hello this is Deploy"
                 '''
                }
            }
        }
    }
}