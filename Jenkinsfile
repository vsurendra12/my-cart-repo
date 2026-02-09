pipeline {
    agent {
        label "java-node"
    }
    stags {
        stage ("build") {
            steps {
                timeout( time :30, unit: "seconds")
                echo "testing"
                sleep 20
            }
        }
    }
}
