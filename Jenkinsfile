pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/nareshh49/java-pipeline12.git'
                sh 'ls -lart'
                sh 'javac hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'ls -lsrt'
                sh 'java myhello'
            }
        }
    }
}
