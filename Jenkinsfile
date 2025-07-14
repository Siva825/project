 pipeline{
    agent any
    stages{
        stage('build'){
            tools{
                jdk 'jdk17'
            }
            steps{
                Script{
                    def (course= "deveops")
                    if (course=="devepos")
                    println "hi"
                    else
                    println "bye"

                }
                 
            }
        }
    }
}
