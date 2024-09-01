pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/vivekpr5/tweet-trend-new.git'
            }
        }
    }
}