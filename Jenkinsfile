 pipeline{
    agent any
    tools{
        maven 'Maven 3.9.8'
    }
    stages{
        stage('build'){
            steps{
                echo "hi are you there"
                sh 'mvn --version'
            }
        }
        stage('test'){
            tools{
                jdk 'jdk17'
            }
            steps{
                sh 'mvn --version'
                sh 'java --version'
            }
        }

    }
}
