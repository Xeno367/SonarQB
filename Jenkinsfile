pipeline {
    agent any

    triggers {
        githubPush()
}

    stages {
        stage('Hello from git') {
            steps {
                echo 'Hello github'
            }
        }
    }
}
