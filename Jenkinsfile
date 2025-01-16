pipeline {
    agent any
    stages {
        stage('code_checkout') {
            steps {
                git credentialsId: 'github-jenkins-cred',  url: 'https://github.com/siripatchava/Jenkins-pro.git'
            }
        }
    }
}