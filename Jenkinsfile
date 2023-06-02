pipeline {
    agent any
    stages {
        stage ('Build Bakcend') {
            steps {
                sh 'mvn clean package -DskipTests=true'
            }
        }
    }
        stages {
        stage ('Build Frontend') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}