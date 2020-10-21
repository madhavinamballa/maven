pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cd maven;mvn -B -DskipTests clean package'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }  
    }
  }
}