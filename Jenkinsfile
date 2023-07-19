pipeline {
    agent none
    stages {
        stage('Maven Compile'){
            agent {
                label 'maven'
            }
            steps {
                sh 'mvn compile'
            }
        }
    }
}
