pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/RONALD1510/my-first-repo'
            }
        }
         stage('build'){
             steps{
                 bat 'javac Helloworld.java'
                 bat 'java Helloworld'
             }
         }
      
    }
}
