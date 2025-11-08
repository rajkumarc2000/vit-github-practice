pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/rajkumarc2000/vit-github-practice.git'
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
