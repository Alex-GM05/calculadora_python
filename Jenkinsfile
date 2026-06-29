pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas unitarias de Python...'
                bat '"C:/Users/aleja/AppData/Local/Programs/Python/Python312/python.exe" -m unittest test_calculadora.py'
            }
        }
    }
}
