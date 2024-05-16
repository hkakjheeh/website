pipeline {
    agent any

    stages{
        stage("Checkout scm"){
            steps{
                git branch: 'main', credentialsId: 'a1d9cc49-94ad-4a9a-b27a-970077cf856a', url: 'https://github.com/hkakjheeh/website.git'
            }
        }
    }
}
