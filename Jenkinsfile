pipeline {
  agent any
  stages {
    stage('buildit') {
      steps {
        sh '''sh \'\'\' chmod +x ./testscript.sh
./testscript.sh\'\'\'
'''
      }
    }

  }
}