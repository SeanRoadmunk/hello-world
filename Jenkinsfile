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
                        chmod a+x hello.sh
                        ./hello.sh
                    ''',
                    returnStdout: true
                )
            }
        }
    }
}
