pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				archiveArtifacts '/**'
                echo 'Building..'
            }
        }
    }
}