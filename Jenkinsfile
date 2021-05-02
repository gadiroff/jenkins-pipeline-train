pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Webhook was configured successfully! Yahooooo :)'
            }
        }
        stage('Stage 2') {
            steps {
                sh 'My current branch in git is $BRANCH_NAME'
            }
        }
    }
}
