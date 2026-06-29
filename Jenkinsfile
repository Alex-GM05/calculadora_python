pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas unitarias de Python...'
                bat 'python -m unittest test_calculadora.py'
            }
        }
    }
}
