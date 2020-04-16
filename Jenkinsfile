pipeline {
    agent any
    stages{
        stage ("Master Build"){
            when{
                branch "master"
            }
            steps{
                echo "Bulding Master"
            }
        }
        stage ("Dev Build"){
            when{
                branch "dev"
            }
            steps{
                echo "Building Dev"
            }
        }
    }
}
