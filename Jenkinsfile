pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "echo 'print(\"Hello world\")' > hello.py"
                sh "python3 --version"
                sh "python3 hello.py"
            }
        }
    }
}