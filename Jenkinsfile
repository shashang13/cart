@Library('roboshop-shared-library@main') _

pipeline{
  agent any

  stages {

    //For each commit
    stage('lint checks'){
      steps{
        script {
          nodejs.lintChecks()
        }
      }
    }
  } //End of Stages
}