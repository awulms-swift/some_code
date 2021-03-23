pipeline {
  agent any
  triggers {
   cron('H/1 1 * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger 2'
      }
    }

  }
}
