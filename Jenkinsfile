pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello Deploy'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'Body', subject: 'Subject', to: 'swapnil05sahu@gmail.com'
        }
    }
}
