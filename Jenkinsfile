pipeline {
    agent{
        label 'AGENT-1'
    }
    options{
        timeout(time: 6, unit: 'MINUTES' )
        disableConcurrentBuilds()
    }
    environment{
        DEPLOY_TO = "dev"
        Greeting = "Hello World"
    }
    stages{
        stage('build'){
            steps{
                echo 'this is build'
            }
        }
        stage('test'){
            steps{
                echo 'this is test'
            }
        }
        stage('deploy'){
            steps{
                echo 'this is deploy'
            }
        }
    }
}