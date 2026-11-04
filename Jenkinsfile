pipeline {
    agent any

    stages {
        stage('My-Job') {
            steps {
                echo "Running pipeline on branch: ${env.BRANCH_NAME}"
                echo "Hello World!"
            }
        }
    }

    post {
        success {
            echo "Finished execution for branch ${env.BRANCH_NAME} successfully."
        }
    }
}
