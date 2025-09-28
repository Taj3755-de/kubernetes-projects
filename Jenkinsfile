pipeline {
    agent any
    environment {
        BRANCH_NAME = env.GIT_BRANCH ?: 'main'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
    }
}
