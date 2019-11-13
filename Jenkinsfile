pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean compile'
            }
        }

        stage ('Package Stage') {

            steps {
                    sh 'mvn Package'
            }
        }
    }
}
