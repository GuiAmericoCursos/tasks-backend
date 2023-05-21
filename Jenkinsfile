pipeline {
    agent any
    stages {
        stage ('Build Backend') {
            steps {
                bat 'mvnw clean package -DskipTests=true'
            }
        }
       stage ('Unit Tests') {
            steps {
                bat 'mvn test'
            }
        }
    }
}

