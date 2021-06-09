library('piper-lib-os')
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
// node (){
// cloudFoundryCreateService(
//     cfApiEndpoint : 'https://api.cf.eu10.hana.ondemand.com',
//     cfOrg : '2f317a0ftrial',
//     cfSpace : 'dev',
//     cfCredentialsId : 'global',
//     cfService :  'connectivity',
//     cfServiceInstanceName : 'BusinessPartnerValidation-cs',
//     cfServicePlan : 'lite',
//    // cfCreateServiceConfig : '{\"example\":\"value\",\"example\":\"value\"}',
//    // cfServiceTags : 'list, of, tags',
//     script : this,
// )
// }
