pipeline {
    agent any

stage('Checkout to Custom Folder') {
    steps {
        dir('/home/kabir/develop_code') {
            git branch: 'develop', url: 'https://github.com/GeekyKabir/Intell-DevOps.git'
        }
    }
}

        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
