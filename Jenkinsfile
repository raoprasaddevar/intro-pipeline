pipeline {
  agent any
  stages {
    stage('say hello') {
      steps {
        script {
          pipeline {
            agent any

            stages {
              stage('Say Hello') {
                steps {
                  echo 'Hello World!'
                }
              }
            }
          }
        }

        echo 'test'
      }
    }
    stage('printasdasdasd') {
      steps {
        echo 'printtt'
      }
    }
  }
}