pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    stages{
        stage("devlop"){
            when { expression { BRANCH == 'origin/release'  || BRANCH == 'release' } }
            steps {
                sh "echo devlop"
            }
        }
        stage ("master"){
            when { branch  'master' }
            steps{
                sh "echo master"
            }
        }
    }
}
