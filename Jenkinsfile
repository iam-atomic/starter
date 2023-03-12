pipeline {
    agent {
        docker "alpine"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Stage Build'
                sh "hostname"
            }
        }
        stage('Test') {
            steps {
                echo 'Stage Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Stage Deploy'
            }
        }
    }
}