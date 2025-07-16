pipeline{
    agent {
        label 'java-slave'
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
