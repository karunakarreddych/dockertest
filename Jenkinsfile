pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'apache2 -v'
                echo 'Successfully installed Apache'
            }
        }
    }
}
