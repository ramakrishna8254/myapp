@Library("harilibs") _
pipeline{
    agent any
    stages{
        stage("Maven Build"){
            steps{
                sh 'mvn clean package -DskipTests=true'
            }
        }
    }
}
