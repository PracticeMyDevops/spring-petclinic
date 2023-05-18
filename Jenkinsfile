pipeline{
    agent any
    tools {
    maven 'maven-3.6.3' 
  }
    stages{
        stage("Build Project"){
            steps{
                echo "${BUILD_NUMBER}"
                echo "Hello World"
                sh 'java --version'
                sh 'jenkins --version'
                sh 'mvn --version'
            }
        }
    }
}
