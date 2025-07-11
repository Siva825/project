pipeline{
    agent {
        label'java-slave'
    }
    stages{
        stage('Build'){
            steps{
                retry(5){
                    echo "hi everyone"
                    error "this is giving some error"
                }
                 
            }
        }
        stage('test'){
            steps{
                echo "this is test block"
            }
        }
    }
}
