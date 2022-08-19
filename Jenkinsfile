pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'build a job', wait: true, quietPeriod: 1)
      }
    }

    stage('Test ') {
      steps {
        warnError(message: 'Test ')
      }
    }

    stage('Deploy') {
      steps {
        echo 'Done'
      }
    }

  }
}