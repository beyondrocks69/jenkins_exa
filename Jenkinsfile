pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                echo 'start build'
				sh 'python --version'
				echo 'hello world!'
            }
        }
    }
}