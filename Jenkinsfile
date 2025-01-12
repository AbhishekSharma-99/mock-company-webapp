pipeline {
    agent any  // This specifies that the pipeline can run on any available agent

    stages {
        stage('Build') {
            steps {
                script {
                    // Command to build the application
                    sh './gradlew assemble'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Command to run the tests
                    sh './gradlew test'
                }
            }
        }
    }
}