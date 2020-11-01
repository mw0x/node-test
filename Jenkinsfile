pipeline {
    agent {
        docker { image 'node:12-alpine' }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'node -v'
                sh 'yarn -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
