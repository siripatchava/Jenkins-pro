pipeline {
    agent any
    stages {
        stage('code_checkout') {
            steps {
                git credentialsI: 'github-jenkins-cred'  url: 'git@github.com:siripatchava/Jenkins-pro.git'
            }
        }
    }
}