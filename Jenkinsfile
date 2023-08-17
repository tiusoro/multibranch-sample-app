pipeline {
    agent {label "linux"}
    options {
        buildDiscarder logRotator(artifactDaysToKerepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
        disableConcurrentBuilds()
    }
    stages {
        stage('Hello') {
            steps {
                echo "Hello! Is it me youre looking for..."
            }
        }
    }
}