pipeline {
  agent any
  triggers{
  cron('H/10 * * * *')
}
  stages {
    stage('print') {
      steps {
        echo 'hello from the trigger again'
      }
    }

  }
}
