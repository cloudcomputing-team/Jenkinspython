pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('hello'){
            steps{
                sh 'python3 hello.py'
            }
        }
    
        stage('hellow'){
            steps{
                sh 'python3 hellowipro.py'
            }
        }
        stage('helloj'){
            steps{
                sh 'python3 hellojenkins.py'
            }
        }
    }
}
