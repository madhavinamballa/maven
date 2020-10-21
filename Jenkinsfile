pipeline {
  agent any
  stages {
    stage('build') {
     dir("maven") {
         sh "pwd"
     }
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }  
    }
  }
}