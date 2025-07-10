pipeline{
    agent any
    tools{
        maven 'Maven 3.8.9'
        jdk 'jdk17'
    }
    stages{
        stage('checkout'){
            steps{
                git url : 'https://github.com/Siva825/project.git',
                credentialsId : 'Siva825_git_creds',
                branch : 'main'
            }
        }
        stage('build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
