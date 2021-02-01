pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo 'building and saving artifact'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
