pipeline {
    agent {
        node{
            label "maven-slave"
        }
    }

    stages{
        stage("Clone-code") {
            steps{
               git branch: 'main', url: 'https://github.com/saiful7bd/tweet-trend.git'
            }
        }
    }
    
}    