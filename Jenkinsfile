@Library('piper-lib-os') _

cloudFoundryDeploy(
    script: script,
    deployType: 'standard',
    cloudFoundry: [apiEndpoint: 'https://api.cf.eu10.hana.ondemand.com', appName:'cfAppName', credentialsId: 'CF_CREDENTIALSID', org: '2f317a0ftrial', space: 'dev'],
    deployTool: 'npm'
)
