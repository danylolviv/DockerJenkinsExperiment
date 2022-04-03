 pipeline{
    agent any
    stages{
        stage("Git merge"){
            steps{
            sh "git fetch --all"
            sh "git checkout main"
            sh "git pull"
            sh "git merge origin/${GIT_BRANCH}"
            }
        }
        stage("Build"){
            steps{
                echo "Now we build"
            }
        }
        stage("Test"){
            steps{
                echo "Now we west"
            }
        }
        stage("Deliver"){
           steps{
              echo "Now we deliver"
           }
        }
    }
 }