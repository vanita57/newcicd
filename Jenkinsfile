@Library('piper-lib-os') _

//buildExecute script:this, buildTool: 'mta'

cloudFoundryDeploy(
    script: this ,
    deployType: 'standard',
    cloudFoundry: [apiEndpoint: 'https://api.cf.eu10.hana.ondemand.com', appName:'cfAppName', credentialsId: 'CF_CREDENTIALSID', org: '2f317a0ftrial', space: 'dev']
)
