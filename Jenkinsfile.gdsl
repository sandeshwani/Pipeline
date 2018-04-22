pipeline {
    agent any
    stages {
        stage('eMusicStore') {
            steps {
                echo "test"

            }
            post {
                success {
                    echo "checkout successful"
                }
            }

        }
        stage('Second') {
            steps {
                echo 'Hello world'
            }
        }
    }
}