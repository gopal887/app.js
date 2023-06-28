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
                sh 'npm install'
                sh 'npm run'
            }
        }
    }
}