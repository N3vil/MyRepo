pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
        }
    }
    
    stages {
        stage {
            steps {
                sh 'chmod +x run.py'
                sh 'python run.py'
            }
        }
    }
}
