pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo "${JOB_NAME}"
                echo "${JOB_BASE_NAME}"
                echo "${BUILD_NAME}"
                sh 'echo Hello World! > test.txt'
                sh 'git add test.txt'
                sh 'git status'
            }
        }
    }
}
