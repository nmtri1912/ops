pipeline {
    agent any
    parameters {
        string(name: 'repo_branch', defaultValue: 'dev', description: 'Branch from which build launch')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Build completed"'
            }
        }
    }
}
