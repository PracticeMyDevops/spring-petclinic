pipeline{
    agent any
    stages{
        stage("Build Project"){
            steps{
                echo "${BUILD_NUMBER}"
                echo "Hello World"
                sh 'java --version'
                sh 'jenkins --version'
                sh mvn package
            }
        }
    }
}
