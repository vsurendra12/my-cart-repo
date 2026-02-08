pipeline {
    agent any
    stages {
        stage ("Build-Hello") {
            steps {
                echo "Hello from git repo"
                echo "added this extra line in stage"
                sh "hostname -i"
                echo "added one more line under sh "
            }
        }
    }
}
