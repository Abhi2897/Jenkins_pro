pipeline{
    agent any
    stages{
        stage('Biuld'){
            step{
             sh 'mvn -DskipTests clean package'
            }
        }
         stage('Test'){
            step{
             sh 'mvn test'
            }
        }
    }  
}
