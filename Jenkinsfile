pipeline{
    agent any

    stages{
        stage ('build'){
            steps{
              sh 'pwd'
              sh 'ls'
              sh 'whoami'
              sh 'lscpu'
              sh 'free'
              sh 'lsblk'
              sh 'uptime'
              sh 'top'
            }
        }
        stage ('test'){
            steps{
              echo 'test'
            }
        }
        stage ('deploy'){
            steps{
              echo 'deploy'
            }
        }
    }
}