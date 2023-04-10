pipeline {
    agent any 
    stages {
        stages("stage 1") {
            steps{
                echo "building stage"
            }
        }

        stages("stage 2"){
            steps {
                echo "testing stage"
            }
        }

        stages("stage 3"){
            steps {
                echo "QA stage"
            }
        }
        stages ("stage 4"){
            steps {
                echo "deploy stage"
            }
        }
        stages ("stage 5"){
            steps {
                echo "monitor stage"
            }
        }
    }
}