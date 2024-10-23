pipeline {
    agent any
    stages{
        stage("checkout"){
            steps{
                checkout scm
            }
        }

        stage("Test"){
            steps{
                sh 'npm test'
            }
        }

        stage("Build"){
            steps{
                sh 'npm run build'
            }
        }
        stage("Build Image"){
            steps{
                sh 'docker build -t node-app:1.0 .'
            }
        }
        stage('Docker Push') {
            steps {
                withCredentials([usernamePassword(passwordVariable: 'DOCKERHUB_PASSWORD', usernameVariable: 'DOCKERHUB_USERNAME')]) {
                    sh 'docker login -u $DOCKERHUB_USERNAME -p $DOCKERHUB_PASSWORD'
                    sh 'docker tag node-app:1.0 anubhcv/node-app:1.0'
                    sh 'docker push anubhcv/node-app:1.0'
                    sh 'docker logout'
                }
            }
        }
    }
}
