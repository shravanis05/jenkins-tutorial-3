pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run App') {
            steps {
                bat '"C:\\Users\\durva\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
            }
        }
    }
}
