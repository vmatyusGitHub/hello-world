pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo "${BRANCH_NAME}"
                echo "${branch_name}"
                sh 'echo Hello World! > test.txt'
                sh 'git add test.txt'
                sh 'git status'
                sh 'git commit'
            }
        }
    }
}
