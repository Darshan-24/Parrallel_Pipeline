pipeline {
    agent any
    stages {  
        stage('DevOps')
        {
           parallel {
                stage('Jenkins') {
                    
                    steps {
                        sh "echo Jenkins concept"
                    }
                    
                }
                stage('Git') {
                    
                    steps {
                        sh "echo Git concept"
                    }
                   
                }
            }
        }
}
}
