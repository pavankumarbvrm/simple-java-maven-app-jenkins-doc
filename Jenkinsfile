pipeline {
    node {
    stages {
        stage ('Example Build') {
            steps {
                sh 'mvn --version'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
    }
}
