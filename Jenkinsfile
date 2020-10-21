pipeline {
    agent any
    tools { maven "Maven"}
    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                    sh 'mvn clean compile'
                }
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