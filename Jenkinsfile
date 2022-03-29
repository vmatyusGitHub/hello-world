pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo "${branch}"
                sh 'echo Hello World! > test.txt'
                sh 'git add test.txt'
                sh 'git status'
                sh 'git commit'
            }
        }
    }
}
