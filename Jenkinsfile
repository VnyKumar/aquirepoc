pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Hello World'
                //git checkout
               // git clone 'https://github.com/VnyKumar/aquirepoc.git'
            }
        }
        stage('aws-lambda function creation') {
            steps {
                
                echo 'Hello World inaws lambda'
                git branch: 'main', credentialsId: 'Github-Cred', url: 'https://github.com/VnyKumar/aquirepoc'
            }
        }
        stage('deplooy') {
            steps {
                echo 'Hello World'
                //upload zip it to function
            }
        }
    }
}
