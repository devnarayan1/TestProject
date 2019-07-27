pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				zipFile: 'output.zip' -x 'Jenkinsfile' -x '*.md' archive: false, glob: '/**'
                echo 'Building..'
            }
        }
    }
}