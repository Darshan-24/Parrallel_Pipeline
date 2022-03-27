pipeline {
    agent any
    stages {
        stage('DevOps') {
            parallel {
                stage('Git') {
                    
                    steps {
                        sh "echo Git stage"
                    }
                    
                }
                stage('Jenkins') {
                    
                    steps {
                        sh "echo Jenkins stage"
                    }
                   
                }
                
                post {
                    always {
                        cleanWs()
                    }
                }
            }
                
            }
        }
}

