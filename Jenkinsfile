pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("devlop"){
            when { branch 'devlop' }
            steps {
                sh "echo devlop"
            }
        }
        stage ("master"){
            when { branch  'master' }
            steps{
                sh "echo masterr"
            }
        }
    }
}
