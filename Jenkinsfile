pipeline{
    agent{
        docker{
            image 'davideias/docker_example:latest'
        }
    }
    stages{
        stage('boh') {
            steps {
                sh 'java --version'
            }
        }
    }
}
    
