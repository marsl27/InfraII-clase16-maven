pipeline {
    agent any
    tools {
        maven "maven-nodo-principal"
    }
    stages{
        stage('Build') {
            steps {
                dir (‘maven-adderapp’) {
                    sh 'mvn -DskipTests clean package'
                }
            }
        }
    }
}