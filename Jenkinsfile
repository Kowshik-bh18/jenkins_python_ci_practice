pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo "Cloning GitHub repository..."
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 hello.py'
            }
        }

        stage('Success Message') {
            steps {
                echo "Pipeline executed successfully!"
            }
        }

    }
}