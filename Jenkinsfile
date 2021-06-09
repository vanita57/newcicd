library('piper-lib-os')
pipeline {
    agent any

    stages {
        stage('cloudFoundryCreateService') {
            steps {
                echo 'cloudFoundryCreateService..start'
                cloudFoundryCreateService script: this
            }
        }
        
    }
}
