pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ new_cpp_file.cpp -o lala_task5'
                echo 'Build Successful'
            }
        }
        stage('Test') {
            steps {
                sh 'lala_task5'
                echo 'Test Successful'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Successful'
            }
        }
    }
}
