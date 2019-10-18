pipeline {
  agent any
  environment {
    key1 = 'value1'
    key2 = 'value2'
  }
  stages {
    stage('Example') {
      environment {
        key3 = 'value3'
      }
      steps {
        sh 'echo $key1'
        sh 'echo $key2'
        sh 'echo $key3'
      }
    }
  }
}
