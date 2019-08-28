pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        build(job: 'Job1', quietPeriod: 1, wait: true)
      }
    }
  }
}