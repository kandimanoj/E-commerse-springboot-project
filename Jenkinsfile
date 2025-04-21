pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    sh 'mvn clean package'
                }
            }
        }
        stage('Run') {
            steps {
                script {
                    sh 'java -jar target/your-spring-boot-app.jar'
                }
            }
        }
    }
}
