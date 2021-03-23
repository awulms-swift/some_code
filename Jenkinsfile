pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello awulms'
      }
    }

  }
  triggers {
    cron('H/15 1 * * *')
  }
}
