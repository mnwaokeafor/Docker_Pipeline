
    node{
        stage('Git Checkout') {
            git 'https://github.com/mnwaokeafor/Docker_Pipeline.git'
        }
        stage('Maven Package') {
            sh 'mvn clean package'
        }

        stage('Build Docker Image') {
            sh 'docker build -t mnwaokeafor/my-app:0.0.1 .'
        }
    }

