pipeline {
    agent any 

    stages {
        /* stage('checkout') {
            steps {
                git branch: 'initial_branch', url: "https://github.com/SeanRoadmunk/hello-world.git"
            }
        } */
        stage('run') {
            steps {
                sh (
                    script: '''
                        echo "testing 1 2 3"
                    ''',
                    returnStdout: true
                )
            }
        }
    }
}
