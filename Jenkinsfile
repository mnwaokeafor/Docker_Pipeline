pipeline{
    node{
        stage('Git Checkout') {
            git 'url'
        }
        stage('Maven Package') {
            sh 'mvn clean package'
        }

        stage('Build Docker Image') {
            sh 'docker build -t '
        }
    }
}
