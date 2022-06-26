pipeline{
    agent any
    tools{
       maven 'maven'
    }
    stages{
       stage('Mvn Build'){
                steps{
                   sh 'mvn clean package'
                   sh 'mv target/myweb*.war target/myweb.war'
                }
            }
               
    }
}
