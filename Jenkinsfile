pipeline {
  agent any
  stages {
    stage('Source Discovery') {
      steps {
        bat 'C:\\Python27\\SMS_Jenkins\\AzureScripts\\ConnectionTest.bat'
      }
    }
    stage('Migration_script') {
      steps {
        bat 'C:\\Python27\\SMS_Jenkins\\AzureScripts\\Migration_script.bat'
      }
    }
  }
}