pipeline {
    agent any
    stages {
        stage ('Build Backend') {
            steps {
                bat 'mvnw clean package -DskipTests=true'
            }
        }
       
     }
}

