pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Install Requirements') {
            steps {
                bat 'pip install -r requirements.txt'
            }
        }
        

        // stage('Groovy'){
        //     steps {
        //         script {
        //             t = load 'task7.groovy'
        //             t.testfunc('production')
        //         }
        //     }
        // }
    }
}
