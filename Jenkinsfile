pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo "${BRANCH_NAME}"
                echo "${JOB_NAME}"
                echo "${JOB_BASE_NAME}"
                sh 'echo Hello World! > test.txt'
                sh 'git add test.txt'
                sh 'git status'
            }
        }
    }
}
