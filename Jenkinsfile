pipeline {
    agent {docker { image 'python:3.5.1' }}
    stages {
        stage('build') {
            steps {
                echo 'start build'
				bat 'python --version'
				echo 'hello world!'
            }
        }
    }
}