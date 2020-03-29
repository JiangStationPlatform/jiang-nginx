pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo '==>start run'
                sh 'cd docker && docker-compose down && docker-compose up -d'
            }
        }
    }
}