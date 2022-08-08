pipeline{
    agent any
    stages{
        stage('Biuld'){
            steps{
             sh 'mvn -DskipTests clean package'
            }
        }
         stage('Test'){
            steps{
             sh 'mvn test'
            }
        }
    }  
}
