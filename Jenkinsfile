pipeline {
  agent any
  stages {
    stage('buildit') {
      steps {
        sh '''chmod +x ./testscript.sh
                ./testscript.sh > scriptfile.txt'''
      }
    }

    stage('post') {
      steps {
        archiveArtifacts 'scriptfile.txt'
      }
    }
    stage('print'){
    	steps{
		echo "trigger added"
	}
      }

  }
}
