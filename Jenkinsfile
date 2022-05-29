pipeline {
  agent any
  triggers {
   githubPush()
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello this is from the trigger'
      }
    }
    stage('print') {
    	steps{
    		echo 'hello how are you bala krishna'
	}
	}

  }
}
