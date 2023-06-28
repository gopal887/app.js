pipeline{
    agent any
    stages{
        stage('continuous download'){
            steps{
                 git branch: 'master',url: 'https://github.com/gopal887/react.js.git'
            }
        }
        stage('continuous build'){
            steps{
                sh 'sudo apt install nodejs -y'
                sh 'sudo apt install npm -y'
                sh 'npm install'
                sh 'npm run'
            }
        }
    }
}