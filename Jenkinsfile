pipeline {
    agent any
    
    stages {
        stage('git SCM') {
            steps {
                echo "This is code fetch stage"
            }
        }
        stage('Build') {
            steps {
                echo "This is a build stage"
            }
        }
        stage('Test') {
            steps {
                echo 'This is test stage'
            }
        }
        stage('deploy') {
            steps {
                echo 'This is deploy stage'
            }
        }
    }
}
