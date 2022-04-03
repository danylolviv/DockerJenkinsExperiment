 pipeline{
    agent any
    triggers{
        pollSCM("* * * * *")
    }
    stages{
        stage("MyFirstStage"){
            steps{
            echo "Yay we are running"
            }
        }
    }
 }