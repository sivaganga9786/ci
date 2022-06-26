pipeline{
    agent any
    tools{
       maven 'maven'
    }
    stages{
       stage('Mvn Build'){
                steps{
                   sh 'mvn clean package'
                }
            }
    
    }
}
