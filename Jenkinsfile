pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/AryanSan09/helloworld.git'
            }
        }

        stage('Deploy') {
            steps {
                script {
                    bat 'copy index.html C:\\xampp\\htdocs\\index.html'
                }
            }
        }
    }
}
