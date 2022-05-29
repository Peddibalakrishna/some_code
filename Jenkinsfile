pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello this is from the trigger'
      }
    }
    stage('print') {
    	steps{
    		echo 'hello how are you'
	}
	}

  }
}
