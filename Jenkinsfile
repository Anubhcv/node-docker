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
        //  stage("Login to DockerHub") {
        //     steps {
        //         script {
        //             // Login to DockerHub
        //             def dockerhub_creds = credentials('docker-log')
        //             sh "echo ${dockerhub_creds.password} | docker login -u ${dockerhub_creds.username} --password-stdin"
        //         }
        //     }
        // }

        // stage("Push Image") {
        //     steps {
        //         sh 'docker push anubhcv/node-app:1.0'
        //     }
        // }

        
    }
}
