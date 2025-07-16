
pipeline{
    agent {
        label 'java-slave'
    }
    tools{
        maven 'Maven 3.8.9'
    }
    stages{
        stage('build'){
            steps{
                echo "this is maven"
                sh 'mvn --version'
            }
        }
    }
}
