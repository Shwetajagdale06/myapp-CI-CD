pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo "🔁 Cloning GitHub Repo..."
                checkout scm
            }
        }

        stage('List Files') {
            steps {
                echo "📂 Project Directory:"
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo "⚙️ Add your build steps here (npm install, make, etc.)"
            }
        }
    }
}
