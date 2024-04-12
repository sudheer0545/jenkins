pipeline {
    agent {
        label 'java-slave'
    }
    tools {
        maven 'MAVEN_HOME'
    }
    stages {
        stage("Build") {
            steps {
                echo "hello welcome to tool section"
                sh "mvn --version"
            }
        }
        stage("cartmaven") {
            tools {
                jdk 'jdk-17'
            }
            steps {
                echo "hello, welcome to tool section"
                sh 'mvn --version'
            }
        }
    }
}
