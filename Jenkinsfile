pipeline {
    agent any
    stages{
        stage('git'){
            steps('clone'){
                git 'https://github.com/openmrs/openmrs-core.git'
            }
        }
    stage('mvn package'){
        steps('build package'){
            sh "mvn clean package"
            }
        }
    }
}
