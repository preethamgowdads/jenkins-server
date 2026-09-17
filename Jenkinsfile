pipeline {
    agent any

    stages {
        stage('Read file') {
            steps {
                     echo 'This pipeline runs from my GitHub Jenkinsfile!'
                sh 'ls -l'
                sh 'cat README.md'
            }
        }
    }
}
