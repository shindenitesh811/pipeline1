pipeline {
  agent any
  stages {
    stage('send email') {
      steps {
        emailext(subject: 'Build', body: 'Build is successful', to: 'niteshshindee82@gmail.com')
      }
    }
  }
}