pipeline{
    agent {
        label'java-slave'
    }
    stages{
        stage('Build'){
            steps{
                echo "hi everyone"
                error "this is giving some error"
            }
        }
    }
}
