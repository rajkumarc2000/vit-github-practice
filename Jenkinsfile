pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                checkout scm
            }
        }
        stage('Hello2') {
            steps {
                echo 'Hello World2'
                sleep 5
            }
        }
        stage('Hello3') {
            steps {
                echo 'Hello World3'
                sleep 5
            }
        }
    }
}
