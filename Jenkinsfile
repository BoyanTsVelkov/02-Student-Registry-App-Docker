pipeline{
    agent{
        label any
    }
    stages{
        stage("Install dependencies"){
             steps{
                echo "========installing dependencies========"
                sh "npm install"
            }
        }
        stage("Run tests"){
            steps{
                echo "========running tests========"
                sh "npm test"
            }
        }
    }
}