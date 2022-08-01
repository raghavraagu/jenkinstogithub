pipeline {
    agent none
    stages {
        stage ("run on master code") {
            agent { label "master"}
            steps {
                sh "hostname -I"
            }
        }
        stage ("run on slave1 code") {
            agent { label "php-java-slave1"}
            steps {
                sh "hostname -I"
            }
        }
        stage ("run on slave2 code") {
            agent { label "go-slave2"}
            steps {
                sh "hostname -I"
            }
        }
        stage ("run on slave3 code") {
            agent { label "angular-slave3"}
            steps {
                sh "hostname -I"
            }
        }
        stage ("run on slave4 code") {
            agent { label "react-slave4"}
            steps {
                sh "hostname -I"
            }
        }
        
    }
}
