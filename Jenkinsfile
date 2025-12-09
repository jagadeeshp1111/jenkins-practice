pipeline{
    agent {
        label'AGENT-1'
    }
    environment{
        COURSE='jenkins'
    }
    options{
        timeout{time: 5,unit:'SECONDS'}
    }
        stages{
              stage('Build'){
                    steps{
                            echo 'Building'
                    }
            }
              stage('Test'){
                    steps{
                            echo 'Testing'
                    }
            }
              stage('Deploy'){
                    steps{
                            echo "Deploying"          
                    }
            }
           }
    post{
        always{
            echo "I always say hello again"
        }
    }
}