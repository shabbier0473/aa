pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("build"){
            steps {
                sh "mvn compile"
                sh "mvn test"
                sh "mvn package"
                sh  "mvn install"
            }
        }
        stage ("test"){
            steps{
                sh "mvn test"
    }
         stage("deploy"){
                sh "echo "hello" "
}
