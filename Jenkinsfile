pipeline {
    agent  {
    node {
        label 'AGENT-1'
        
    }
}
    stages {
        stage('Build') { 
            script{
                sh """
                    echo "Building"
                """
            }
        }
        stage('Test') { 
            script{
                sh """
                    echo "Building"
                """
            }
        }
        stage('Deploy') { 
            script{
                sh """
                    echo "Building"
                """
            }
        }
    }
    post{
        always{
            echo 'i will always say hello again!'
            cleanWs()
        }
        success{
            echo 'i will run if success'
        }
        failure{
             echo 'i will run if failure'
        }
    }
}