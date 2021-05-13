@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        customDefaultsCredentialsId :no
        setupCommonPipelineEnvironment script:this
        
    }
    stage('deploy') {
    cloudFoundryDeploy script: this
}
}
