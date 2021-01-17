pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
        }
    }
    
    stages {
        stage ('Hello Test'){
            steps {
                sh 'chmod +x run.py'
                sh 'python run.py'
            }
        }
    }
}
