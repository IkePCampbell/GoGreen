pipeline {
  agent any
  stages {
    stage('') {
      steps {
        powershell(script: '$fileContent = -join ((65..90) + (97..122) | Get-Random -Count 5 | % {[char]$_})', returnStatus: true)
      }
    }
  }
}