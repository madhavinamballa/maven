pipeline {
    agent any
    tools { maven "Maven"}
    stages {
        stage ('Build') {

            steps {
            sh 'mvn -B clean compile'
            }
        }
        stage ('Testing Stage') {

            steps {
                echo "testing"
                }
            }
        }
        stage ('Install Stage') {
            steps {
                echo "deploying"
                }
            }
        }
    }
}