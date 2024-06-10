pipeline {
    agent {
        node{
            label "maven-slave"
        }
    }
enviornment{
  PATH = "/opt/apache-maven-3.9.4/bin:$PATH"
}
    stages{
        stage("Build") {
          steps{
            sh 'mvn clean deploy'
          }
        }
    }
    
}    