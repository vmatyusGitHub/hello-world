pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'echo Hello World! > test.txt'
                sh 'git add test.txt'
                sh 'ls'
            }
        }
    }
}
