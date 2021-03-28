/* Maven Example */

pipeline {
    tools {
        maven 'Maven 3.6.3'
        jdk 'java-11-openjdk'
    }
    agent any
    /* agent { docker { image 'maven:3.6.3' } } */
    stages {
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}


