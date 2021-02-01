pipelines {
    stages {
        stage ('build') {
            stage {
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts 'dist/trainSchedule.zip'
            }
        }
    }
}
