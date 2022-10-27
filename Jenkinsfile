pipeline {
  agent any
  stages {
    stage('email ahmed') {
      steps {
        mail(subject: 'subject', body: 'srerererer', to: 'eng.ahmed.demir@gmail.com')
        emailext(subject: 'subject extended', body: 'extendeds', from: 'eng.ahmed.demir@gmail.com', to: 'eng.ahmed.demir@gmail.com')
      }
    }

  }
}