pipeline {
    agent {
        label "java-node"
    }
    stages {
        stage ("build_within_time") {
            steps {
                timeout (time : 30, unit : "SECONDS") {
                    echo "sleeping 30 sec"
                    sleep 60
                }
            }
        }
    }
  }
