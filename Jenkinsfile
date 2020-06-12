pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("build"){
            when { branch 'devlop' }
            steps {
                sh "mvn compile"
            }
        }
        stage("test"){
            when { branch 'devlop' }
            steps{
                sh "mvn test"
            }
        }
        stage ("deploy"){
            when { branch  'master' }
            steps{
                sh "echo deployed"
            }
        }
    }
}
