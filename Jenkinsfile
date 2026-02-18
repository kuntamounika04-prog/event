pipeline {
    agent any

    stages {
        stage('Build html website') {
            steps {
               publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: '', reportFiles: 'Register.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
