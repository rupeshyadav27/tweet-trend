pipeline {
    agent {
        node {
            label 'maven-sslave'
        }
    }
environment {
    PATH = "opt/apache-maven-3.9.8/bin:$PATH"
}

    stages {
        stage("build"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
