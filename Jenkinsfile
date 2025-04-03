pipeline {
    agent any

    stages {
         stage('hello'){
            steps{
                sh 'python3 hello.py'
            }
        }
          stage('hellojenkins'){
            steps{
                sh 'python3 hellojenkins.py'
            }
          }
          
           stage('hellowipro'){
            steps{
                sh 'python3 hellowipro.py'
            }
           }
           
    }
}
