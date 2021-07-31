pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "This is build step"
                sh 'echo using shell within Jenkinsfile ZZZZZZZZZZZ'
                echo 'not using shell in the Jenkinsfile ZZZZZZZZZ'
                echo 'Bu satiri Zarifjan Baltayev Ekledi'
            }
        }
    }
}