 pipeline{
    agent any
    tools{
        maven 'Maven 3.9.8'
    }
    stages{
        stage('build'){
            tools{
                jdk 'jdk17'
            }
            steps{
                sh "hostname -i"
                sh "mvn --version"
                sh "mvn package"
            }
        }
    }
}
