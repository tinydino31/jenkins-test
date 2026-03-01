pipeline {
    agent any
    stages {
        stage('Info') {
            steps {
                echo "JENKINS_URL = ${env.JENKINS_URL}"
                echo "BUILD_ID = ${env.BUILD_ID}"
            }
        }
    }
}
