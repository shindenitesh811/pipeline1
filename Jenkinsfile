pipeline {
  agent any
  stages {
    stage('poll scm') {
      steps {
        mail(subject: 'Success', body: 'Build is successful', to: 'shindenitesh811@gmail.com')
      }
    }
  }
}