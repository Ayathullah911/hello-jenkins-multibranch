pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning the branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Build') {
            steps {
                echo "Simulating Build Stage..."
            }
        }
        stage('Test') {
            steps {
                echo "Running unit tests (simulated)"
            }
        }
        stage('Deploy') {
            when {
                branch 'main'
            }
            steps {
                echo "Deploying main branch to production (simulated)"
            }
        }
    }
}
