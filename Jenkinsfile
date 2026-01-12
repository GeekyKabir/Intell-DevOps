pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code into a folder inside Jenkins workspace
                git branch: 'develop', url: 'https://github.com/GeekyKabir/Intell-DevOps.git'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
