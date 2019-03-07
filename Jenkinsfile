pipeline {
    agent any 

    stages {
        stage('Go!') {
            steps {
                sh (
                    script: '''
                        bash hello.sh
                    '''
                    returnStdout: true
                )
            }
        }
    }
}
