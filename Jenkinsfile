

node () {
  stage('Lifecycle Evaluation'){
    nexusPolicyEvaluation(
         iqApplication: 'Struts-Avantor',
         iqInstanceId: 'NexusIQ',
         iqScanPatterns: [[scanPattern: '**/*.jar'], [scanPattern: '**/**']],
         iqStage: 'stage-release'
    )
  }
}
