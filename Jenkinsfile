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
<<<<<<< HEAD
         stage("deploy"){
                sh  "shabbir"
=======
>>>>>>> 167690b64494892834744c5a2644e08e278c7fa8
}
