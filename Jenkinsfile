pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				zip zipFile: 'entities.zip', archive: false, glob: '/**'
                echo 'Building..'
            }
        }
    }
}