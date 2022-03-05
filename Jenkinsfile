pipeline {

    agent {
        dockerfile true
    }

    stages {

        stage("build") {

            steps {
                echo 'Hello World!'
                sh 'echo dupa = $dupa1'
            }
        }
    }
}