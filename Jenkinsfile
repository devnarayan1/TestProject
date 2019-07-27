pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				bat 'del entities.zip'
				zip zipFile: 'entities.zip', archive: true, glob: '/**'
                echo 'Building..'
            }
        }
    }
}