pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'docker exec -it /bin/bash'
                sh 'mvn --version'
            }
        }
    }
}
