pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "This is build step"'
          }
        }
        stage('Parallel Build') {
          environment {
            name = 'nitesh'
          }
          steps {
            sh 'echo "this is a parallel build"'
          }
        }
      }
    }
  }
  environment {
    name = 'nitesh'
  }
}