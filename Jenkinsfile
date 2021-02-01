pipelines {
    stages {
        stage ('build') {
            stage {
                sh './gradlew build'
                archiveArtifacts artifacts 'dist/trainSchedule.zip'
            }
        }
    }
}
