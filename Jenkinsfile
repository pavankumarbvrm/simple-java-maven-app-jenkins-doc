pipeline {
    agent none
    stages {
        stage ('Example Build') {
            steps {
                sh 'mvn --version'
                sh 'mvn -B -DskipTests clean package'
            }
        }
        stage ('Example Test') {
            steps {
                'java -version'
            }
        }
    }
}
