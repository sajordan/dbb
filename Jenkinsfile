pipeline {
    agent any
    stages {
        stage('Git Source') {
            steps {
        git credentialsId: '0ae75ced-068a-40df-94e0-fb3f9a3089c7', url: 'https://github.com/sajordan/dbb.git'
            }    
        }
        stage('Build') {
            steps {
                echo 'Run Compile'
                echo 'Compile Step 2'
                echo 'Compile Step 3'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
                echo 'Testing Step 5'
            }
        }
        stage('Deploy') {
            steps {
                echo 'UCD Deploy'
                echo 'Deploy Step 7'
            }
        }
    }
}
