pipeline {

    agent any

    stages {
        stage('build') {
            steps {
                echo 'build job for front-end nodejs application'
                sh 'npm install'
            }
        }
    }

    stages {
        stage('test') {
            steps {
                echo 'test job for front-end nodejs application'
                sh 'npm test'
            }
        }
    }

    stages {
        stage('package') {
            steps {
                echo 'package job for front-end nodejs application'
                sh 'npm run package'
            }
        }
    }

}