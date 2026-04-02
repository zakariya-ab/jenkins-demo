pipeline{
    agent any

    stages{
        stage('Build') {
            steps{
                echo 'Build en cours...'
            }
        }

        stage('Test') {
            steps{
                echo 'Tests en cours...'
            }
        }

        stage('Execution Script') {
            steps{
                bat 'test.bat'
            }
        }

        stage('deploy') {
            steps{
                echo 'Deploiement simule...'
            }
        }
    }
}