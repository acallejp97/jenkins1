pipeline {
    agent any
    environment{
        fichero = "/etc/passwd"
    }
    stages {
        stage('Mostrar fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Mostrar usuarios') {
            steps {
                sh 'wc -l ${fichero}'
            }
        }
    }
}
