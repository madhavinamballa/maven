pipeline {
    agent any
    tools { maven "Maven"}
    stages {
        stage ('Build') {

            steps {
            sh 'mvn -B clean compile'
            }
        }
    }
}
        