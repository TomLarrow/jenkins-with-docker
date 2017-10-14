pipeline{
    agent {label 'master'}

    environment {
        imageTag = "tomlarrow/jenkins-with-docker"
    }

    stages {
        stage ('build') {
            steps {
                sh "docker build -t ${imageTag} ."
            }
        }
    }
}