pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo "just a simple build stage running"
                sh 'cat hello.txt'
            }
        }

        stage("Done") {
            steps {
                echo "Build completed. You can add more here later."
            }
        }
    }
}
