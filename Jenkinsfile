pipeline{
    agent any
    tools{
        maven 'Maven 3.9.8'
    }
    stages{
        stage('build'){
            steps{
                sh "hostname -i"
                sh "mvn --version"
                sh "mvn package"
            }
        }
    }
}
