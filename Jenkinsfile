pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'application is building'
            }
        }
        stage('testing'){
            steps{
                echo 'Automation testing'
            }
        }
        stage('UAT') {
            steps {
                echo 'waiting for UA'
            }
        }
        stage('release') {
            steps {
                echo 'application is ready to release to prod services'
            }
        }
        stage('dev') {
            steps {
                echo 'application is developed and building'
            }
        }
    }
}
