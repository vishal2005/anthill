pipeline {
    agent any
    tools {
        ant 'ant3'
        maven 'maven4.1'
    }
    stages{
        stage('Install') {
            steps {
                sh  'ant -version'
                sh  'ant compile'
                sh  'mvn --version'
                sh  'mvn clean'
        }
    }
 }
}
