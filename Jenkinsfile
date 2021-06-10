library('piper-lib-os')
node {
    stage('cloudFoundryCreateService') {
cloudFoundryCreateService(
    cfApiEndpoint : 'https://test.server.com',
    cfOrg : 'cfOrg',
    cfSpace : 'cfSpace',
    cfCredentialsId : 'cfCredentialsId',
    cfService :  'myService',
    cfServiceInstanceName : 'myServiceInstanceName',
    cfServicePlan : 'myPlan',
   // cfCreateServiceConfig: '{\"example\":\"value\",\"example\":\"value\"}',
   // cfServiceTags: 'list, of, tags',
    script: this,
)
    }
 

}
