import groovy.json.JsonOutput

pipeline {
    agent {
        label "dsportal-test-node"
    }
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
            }
        }
    }
}
