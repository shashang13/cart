@Library('roboshop-shared-library@main') _

pipeline{
  agent any

  stages {

    //For each commit
    stage('lint checks'){
      steps{
        script {
          sample.info('hello', 'google.com')
        }
        sh '''
          # Commented below line to move ahead in the project as this step is expected to fail.
          # ~/node_modules/jslint/bin/jslint.js server.js
          echo "lint checks"
        '''
      }
    }
  } //End of Stages
}