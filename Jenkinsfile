pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo \'test1\''
      }
    }
    stage('printing msg') {
      steps {
        echo 'testing print'
        mail(subject: 'test Multibranch Pipeline', body: 'test Multibranch Pipeline', to: 'viky@contentsphere.com')
      }
    }
  }
}