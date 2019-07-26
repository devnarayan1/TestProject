pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				zip zipFile: 'output.zip', archive: false, glob: '/**'
                echo 'Building..'
            }
        }
    }
}