pipeline{
    agent any
    tools{
        maven 'Maven 3.8.9'
        jdk 'jdk17'
    }
    stages{
        stage('build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
