pipeline{
    agent{
        label 'java-slave'
    }
    stages{
        stage('build'){
            steps{
                timeout(time:10, unit:'SECONDS'){
                echo "******go ahead*********"
                sleep 30                   
                }
            }
        }
    }
}
