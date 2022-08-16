pipeline{
    agent any
    stages{
        stage("git"){
            steps{
            git 'https://github.com/monaaws/maven-pro.git'
            }
        }
        stage('maven initialize'){
           steps{
           bat "mvn initialize"
           }
        }   
        stage('maven build') {
            steps{
            bat "mvn package"
            }
        }
        stage('maven compile'){
            steps{
            bat "mvn compile"    
            }
        }
    

    }
}
