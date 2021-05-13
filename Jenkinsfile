@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        customDefaultsCredentialsId script:this
        setupCommonPipelineEnvironment script:this
        
    }
    stage('deploy') {
    cloudFoundryDeploy script: this
}
}
