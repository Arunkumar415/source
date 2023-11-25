pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                git 'https://github.com/Arunkumar415/simple-java-maven-app.git'
            }
        }
    }
}
