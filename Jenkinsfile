pipeline {
    agent{
        label 'AGENT-1'
    }
    options{
        timeout(time: 8, unit: 'MINUTES' )
        disableConcurrentBuilds()
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