pipeline {
    agent any

    stages {
        stage('Trigger Remote Job') {
            steps {
                script {
                    // Lancer un autre job Jenkins (local, sur le même serveur Jenkins)
                    build job: 'remotepipeline', wait: true
                }
            }
        }
    }
}
