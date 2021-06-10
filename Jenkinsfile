@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('cloudFoundryCreateService') {
        cloudFoundryCreateService(
    cfApiEndpoint : 'https://test.server.com',
    cfOrg : 'cfOrg',
    cfSpace : 'cfSpace',
    cfCredentialsId : 'cfCredentialsId',
    cfService :  'myService',
    cfServiceInstanceName : 'myServiceInstanceName',
    cfServicePlan : 'myPlan',
    //cfCreateServiceConfig : '{\"example\":\"value\",\"example\":\"value\"}',
   // cfServiceTags : 'list, of, tags',
    script : this,
)
}
}
