

node () {
  stage('Lifecycle Evaluation'){
    nexusPolicyEvaluation(
         iqApplication: 'Struts-Avantor',
         iqInstanceId: 'Nexus IQ Server',
         iqScanPatterns: [[scanPattern: '**/*.jar'], [scanPattern: '**/**']],
         iqStage: 'stage-release'
    )
  }
}
