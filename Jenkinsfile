 pipeline{
    agent any
    trigger{
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