pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                echo 'Run the static analysis to the code' 
            }
        }
        stage('Build') {
            steps {
                echo 'Compile the source code' 
            }
        }
        stage('Security Check') {
            steps {
                echo 'Run the security check against the application' 
            }
        }
        stage('Caculate version') {
            steps {
                echo 'Run unit tests from the source code' 
            }
        }
        stage('Security check') {
            steps {
                echo 'Run only crucial integration tests from the source code' 
            }
        }
        stage('Publish Artifacts') {
            steps {
                echo 'Save the assemblies generated from the compilation' 
            }
        }
    }
}


