pipeline {
    agent {
        node {
            label 'maven-sslave'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
               git branch: 'main', url: 'https://github.com/rupeshyadav27/tweet-trend.git'
            }
        }
    }
}
