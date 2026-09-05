pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'echo "Hello Jenkins"'
                bat 'date /T'
            }
        }
    }
}
