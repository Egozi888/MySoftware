pipeline {
    agent any

    stages {
        stage('Stage_1') {
            steps {
                sh '''
                    ls -la
                    python3 click.py 
                    python3 welcome.py
                    '''
            }
        }
    }
}
