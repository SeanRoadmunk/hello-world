pipeline {
    agent any 

    stages {
        stage('checkout') {
            git branch: 'initial_branch', url: "https://github.com/SeanRoadmunk/hello-world.git"
        }
        stage('run') {
            steps {
                sh (
                    script: '''
                        bash hello.sh
                    ''',
                    returnStdout: true
                )
            }
        }
    }
}
