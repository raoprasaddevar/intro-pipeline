pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('print abc') {
      steps {
        echo 'ABC'
      }
    }
    stage('deplay') {
      steps {
        mail(subject: 'test', body: 'test from junkins', from: 'prasad@od.com', to: 'prasad.devar@officedepot.com')
      }
    }
  }
}