@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('deploy') {
    customDefaultsCredentialsId :no
    cloudFoundryDeploy script: this
}
}
