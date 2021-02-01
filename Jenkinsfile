pipeline {
    agent any
    stages {
        stage ('Build') {
            stage {
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
