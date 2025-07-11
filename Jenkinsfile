 pipeline{
    agent {
        label 'java-slave'
    }
    tools{
        jdk 'jdk17'
        maven 'Maven 3.8.9'
    }
    stages{
        stage('checkout scm'){
            steps{
                git (
                    branch: 'main',
                    credentialsId: 'Siva825_git_creds',
                    url: 'https://github.com/Siva825/project.git'
                )        
            }
        }
        stage{'build'}{
            tools{
                maven 'Maven 3.9.8'
            }
            steps{
                sh 'mvn validate'
            }
        }
    }
}
