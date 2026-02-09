pipeline {
    agent {
        label "java-node"
    }
    stages {
        stage ("build") {
            steps {
                timeout( time :30, unit: "SECONDS")
                echo "testing"
                sleep 30
            }
        }
    }
}
