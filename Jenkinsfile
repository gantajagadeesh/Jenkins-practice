pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building.. ${Stage_name}"
                sh Test.sh
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. $user_name'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
