pipeline{
    agent any
    stages {
        stage('1-make a left'){
            steps{
                sh 'echo "walk...."'
                sh 'cat /etc/passwd'
            }
        }
        stage ('2- make a right'){
            steps{
                sh 'echo "walk...."'
                sh 'lscpu'
            }
        }
        stage ('3-make a left'){
            steps{
                sh 'echo "walk..."'
                sh 'cat /etc/passwd | grep ubuntu'
                sh 'free -g'
            }
        } 
        stage ('4-cross the street'){
            steps{
                sh 'echo "walk...."'
                sh 'whoami'
            }
        }
    }
}