pipeline {
    agent {
        label 'maven'
    }

    stages {
        stage('Clone-code') {
            steps {
                git 'https://github.com/KunalMansukhani/tweet_trend.git'
            }
        }
    }
}
