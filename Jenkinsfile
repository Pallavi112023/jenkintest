pipeline {
  agent any
  stages {
    stage('python packeg list') {
      steps {
        sh '''python3 -m pip -V
python3 -m pip freeze'''
      }
    }

  }
}