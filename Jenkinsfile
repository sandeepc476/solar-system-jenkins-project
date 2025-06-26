pipeline {
    agent any

    tools {
        node 'nodejs-22-6-0' 
    }
    stages {
        stage('VM Node Version') {
            steps {
                sh '''
                   node -v
                   npm -v
                '''    
            }
        }
    }
}
