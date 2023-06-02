pipeline {
    agent any
    stages {
        stage ('Build Bakcend') {
            steps {
                sh 'mvn clean package -DskipTests=true'
            }
        }
    }
}