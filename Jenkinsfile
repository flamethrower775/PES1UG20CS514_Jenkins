pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'gcc new_cpp_file.cpp -o lala_task5i'
                echo 'Build Successful'
            }
        }
        stage('Test') {
            steps {
                sh './lala_task5'
                echo 'Test Successful'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Successful'
            }
        }
    }
    post {
        failure {
            echo 'Pipeline Failed PES1UG20CS514'
        }
    }
}
