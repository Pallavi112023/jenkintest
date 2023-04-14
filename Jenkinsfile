pipeline {
  agent any
  stages {
    stage('python packeg list') {
      steps {
        sh '''python3 -m pip -V
python3 -m pip freeze'''
      }
    }

    stage('list of files') {
      steps {
        sh '''ls -la
python3 -V
'''
      }
    }

    stage('get python verson') {
      steps {
        sh '''ls -la
python3 -V'''
      }
    }

  }
}