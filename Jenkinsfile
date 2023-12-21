pipeline{
    agent any
    stages{
        stage("mvn validate"){
            steps{
                sh "mvn validate"
            }
        }
        stage("test"){
            steps{
                sh "mvn test"
            }
        }
        stage("clean install"){
            steps{
                sh "mvn clean install"
                echo "installed the packages"
            }
            
        }
    }
}