pipeline {
    agent  {
    node {
        label 'AGENT-1'
        customWorkspace '/some/other/path'
    }
}
    stages {
        stage('Build') { 
            steps {
                echo "Building"
            }
        }
        stage('Test') { 
            steps {
                echo "Testing"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploying"
            }
        }
    }
}