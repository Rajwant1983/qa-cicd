pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-tutorial-test1"
                }
                  dir('$JENKINS_HOME/jobs/$JOB_NAME/builds/$BUILD_NUMBER/archive') {
    // some block
}  
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}
