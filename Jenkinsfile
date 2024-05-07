pipeline { 
    agent {
        labels 'ws'
    }
    stages {
        stage('Lint Checks') {      // Style checks
            steps {
                sh "echo performing Lint Checks"
                
                // sh "mvn checkstyle:check || true"
            }
        }
        stage('Static Code Analysis') {     // security code checks
            steps {
                sh "echo Static Checks ...."
            }
        }
    }
}