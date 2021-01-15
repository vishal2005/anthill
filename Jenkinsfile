pipeline {
    agent any
    tools {
        ant 'ant3'
    }
    stages{
        stage('Install') {
            steps {
                sh  'ant -version'
                sh  'ant compile'
        }
    }
 }
}
