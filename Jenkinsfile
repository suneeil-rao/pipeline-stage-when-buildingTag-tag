pipeline{
    agent any
    
    stages{
        stage('Build'){
            when{
                    buildingTag()
                }
            steps{
                 echo "================ Hello world Building Tag"
            }
        }        
    }
}
