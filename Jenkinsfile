pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changelog '.*some_text*.'
            }
            steps {
                echo "hello World Changelog"
            }
        }
    }
}
