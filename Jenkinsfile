#!/usr/bin/env groovy

pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
                echo '#########111111#########'
                sleep 5
                echo '#########222222#########'
                sleep 5
                echo '#########333333#########'
                sleep 5
                echo '#########444444#########'
                sleep 5
                echo '#########555555#########'
                sleep 5
                echo '#########666666#########'
                sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
    }
}
