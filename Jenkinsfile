pipeline {
  agent any
  stages {
    stage('build ') {
      steps {
        build 'build '
      }
    }

    stage('Test ') {
      steps {
        catchError(buildResult: 'test')
      }
    }

    stage('deploy') {
      steps {
        sh 'pwd'
        echo 'okay'
      }
    }

  }
}