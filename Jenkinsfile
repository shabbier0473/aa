pipeline{
    agent any
    tools { maven "MAVEN_HOME" }
    parameters{
        gitParameter branchFilter: 'origin/(.*)', defaultValue: 'origin/master', name: 'BRANCH', type: 'PT_BRANCH'
        gitParameter name: 'TAG',type: 'PT_TAG', selectedValue: 'NONE'
    }

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
