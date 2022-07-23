pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
				echo 'Hi Snehasri'
                echo "Build"
                echo "PATH - $PATH"
                echo "BUILDNUMBER - $env.BUILD_NUMBER"
                echo "BUILD_ID - $env.BUILD_ID"
                echo "JOB_NAME - $env.JOB_NAME"
                echo "BUILD_TAG - $env.BUILD_TAG"
                echo  "BUILD_URL - $env.BUILD_URL"
            }
        }
    }
}