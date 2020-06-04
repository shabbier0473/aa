pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("build"){
            steps {
                sh "mvn compile"
            }
        }
    }
}
