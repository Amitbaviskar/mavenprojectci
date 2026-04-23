pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Amitbaviskar/mavenprojectci.git'
            }
        }

        stage('Test') {
            steps {
                echo 'Pipeline working ✅'
            }
        }
    }
}
