pipeline {

    agent any

    environment {
        APP_NAME = "Test-App"
        APP_VERSION = "1.0.0"
        APP_ENV = "dev"
    }

    stages {

        stage("Build") {
            steps {
                echo "===== BUILD STAGE ====="
                echo "Building Application..."
                echo "Application Name : ${env.APP_NAME}"
                echo "Application Version : ${env.APP_VERSION}"
                echo "Application Environment : ${env.APP_ENV}"
            }
        }

        stage("Test") {
            steps {
                echo "===== TEST STAGE ====="
                echo "Testing Application..."
                echo "Application Name : ${env.APP_NAME}"
                echo "Application Version : ${env.APP_VERSION}"
                echo "Application Environment : ${env.APP_ENV}"
            }
        }

        stage("Deploy") {
            steps {
                echo "===== DEPLOY STAGE ====="
                echo "Deploying Application..."
                echo "Application Name : ${env.APP_NAME}"
                echo "Application Version : ${env.APP_VERSION}"
                echo "Application Environment : ${env.APP_ENV}"
            }
        }
    }

    post {

        success {
            echo "peline executed successfully."
        }

        failure {
            echo "Pipeline execution failed."
        }

        always {
            echo " This block always runs, whether the pipeline succeeds or fails."
        }
    }
}
