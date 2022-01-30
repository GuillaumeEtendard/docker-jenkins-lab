pipeline {
    agent any

    tools {nodejs "nodejs"}

    stages {
//        stage('Cloning Git') {
//            steps {
//                git([url: 'https://github.com/GuillaumeEtendard/docker-jenkins-lab.git', branch: 'main'])
//            }
//        }
        stage('Building image') {
            steps {
                sh "docker-compose build"
            }
        }
    }
}

