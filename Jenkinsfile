pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo "${env.BRANCH_NAME}"
                echo "${env.BUILD_NUMBER}"
                echo "${env.BUILD_ID}"
            }
        }
    }
}