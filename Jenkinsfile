pipeline {               // the whole file is wrapped in this

    agent any             // run on any available Jenkins server

    stages {             // contains all your stages

        stage('Build') {   // Stage 1 — give it any name
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {    // Stage 2
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {  // Stage 3
            steps {
                echo 'Deploying...'
            }
        }
    }
}
