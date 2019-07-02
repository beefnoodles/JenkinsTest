pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'pwd'
                sh 'ls /'
                sh 'type java'
                sh 'ls /var/jenkins_home/workspace'
            }
        }
    }
}

