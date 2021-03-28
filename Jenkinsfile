/* Maven Example */

pipeline {
    tools {
        maven 'Maven 3.6.3'
    }
    agent any
    /* agent { docker { image 'maven:3.6.3' } } */
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}


