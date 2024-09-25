pipeline {
    agent any
    
    stages {
        stage('git SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/githubprabha/declarative-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                bat "mvn install"
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
