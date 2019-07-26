pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				output.zip archive '/**'
                echo 'Building..'
            }
        }
    }
}