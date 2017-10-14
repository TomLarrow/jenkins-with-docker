pipeline{
    agent {label 'master'}

    environment {
        imageTag = "tomlarrow/jenkins"
    }

    stages {
        stage ('build') {
            steps {
                sh "docker build -t ."
            }
        }
    }
}