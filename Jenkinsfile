pipeline {
    agent {label 'ubuntu20'}
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/adirgit84/public_declarative_pipeline.git'
            }        
        }
        stage('Build') {
            steps {
                echo 'github trigger test4.'
            }
        //  post {
        //         success {
        //             always { 
        //                 junit '**/target/surefire-reports/TEST-*.xml'
        //                 archiveArtifacts 'target/*.jar'
        //             }
        //         }
        //     } 
        }
    }
}