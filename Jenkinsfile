pipeline {
    agent any
    stages {
        stage('master') {
            when{
                branch 'master'
            }
                steps {
                    echo("I have run my ${env.BRANCH_NAME} branch, the question is, will my child")
                }
        }
        stage('staging') {
            when{
                branch 'staging'
            }
                steps {
                    echo("I have run my ${env.BRANCH_NAME} branch, the question is, will my child")
                }
        }
    }
}