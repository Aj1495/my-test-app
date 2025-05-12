@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        stage('Greet') {
            steps {
                sayHello('bobthe')
            }
        }
        stage('Build') {
            steps {
                echo 'This is where you would build your app!'
            }
        }
    }
}

