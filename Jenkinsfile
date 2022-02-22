pipeline{
        agent any
        stages{
            stage('Clone'){
                steps{
                    sh "mkdir ~/jenkins-tutorial-test"
                }
            }
            stage('Install Docker and Docker-Compose'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}