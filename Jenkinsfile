pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'printenv'
                echo '${env.GIT_BRANCH}'
            }
        }
    }
}
