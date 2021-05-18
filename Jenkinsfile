pipeline {
    agent any

    stages {
        stage('Mostrar fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Mostrar usuarios') {
            steps {
                sh 'wc -l /etc/passwd'
            }
        }
    }
}
