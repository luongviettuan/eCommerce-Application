Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
				cd starter_code
                sh 'mvn --version'
            }
        }
    }
}