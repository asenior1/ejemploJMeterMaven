pipeline {
    agent any

    stages {
        stage('Performance') {
            steps {
                //sh "/usr/local/opt/maven/bin/mvn clean"
                sh './mvnw verify -Pperformance '
            }
        }
    }
}
