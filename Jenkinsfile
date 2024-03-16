pipeline {
    agent { node { label 'AGENT-1' } }
    stages {
        stage('Install dependies') {
        
            steps {
                sh 'npm install'
            }
        }
        stage('unit Test') {
            steps{
                echo "unit testing us done here"
            }
        }
    }
}