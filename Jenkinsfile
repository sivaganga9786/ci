pipeline{
    agent any
    stages{
       stage('Mvn Build'){
                steps{
                    def mvnHome = tool name: 'maven', type: 'maven'
                    sh "${mvnHome}/bin mvn clean package"
                }
            }
    
    }
}
