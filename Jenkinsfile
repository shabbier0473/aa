pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("build"){
            steps {
                sh "mvn compile"
            }
        }
        stage("test"){
            steps{
                sh "mvn test"
            }
        }
        stage ("deploy"){
            steps{
                sh "echo deployed"
            }
        }
    }
         stage("deploy"){
                sh  "shabbir"
}
}
