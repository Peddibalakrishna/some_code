pipeline {
  agent any
  stages {
    stage('buildit') {
      steps {
        sh '''sh \'\'\'chmod +x ./testscript.sh
                ./testscript.sh > scriptfile.txt\'\'\''''
      }
    }

    stage('post') {
      steps {
        sh 'archiveArtifacts artifacts: \'scriptfile.txt\', followSymlinks: false'
      }
    }

  }
}