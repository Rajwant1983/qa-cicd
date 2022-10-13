pipeline{
        agent any
        stages{
                
                 checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Rajwant1983/qa-cicd.git']]])  
        }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }

