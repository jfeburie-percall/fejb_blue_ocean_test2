pipeline {
  agent any
  stages {
    stage('build job') {
      steps {
        build(job: 'TCAD-PTCIC/master', propagate: true, wait: true)
      }
    }
  }
}