pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Msdee87/Dev-Repo.git'
            }
        }
        
        stage("build") {

            steps {
                echo 'building my application...'
            }
        }

        stage("deploy") {

            steps {
              echo 'deploying my application...'
            }
        }

        stage("test") {

            steps {
                echo 'test my application...'
            }
        }
        stage("release") {

            steps {
                echo 'release my application...' 
            }
        }

    }
}