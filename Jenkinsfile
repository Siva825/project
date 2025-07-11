pipeline{
    agent{
        slave'java-slave'
    }
    stages{
        stage('build'){
            steps{
                timeout(time:10,units:'SECONDS'){
                echo "******go ahead*********"
                sleep 30                   
                }
            }
        }
    }
}
