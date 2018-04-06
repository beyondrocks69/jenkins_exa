pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'start build'
				bat 'set %path%'
				bat 'set path = C:\Users\tli56\AppData\Local\Continuum\Anaconda3\;%path%'
				bat 'python --version'
				echo 'hello world!'
            }
        }
    }
}