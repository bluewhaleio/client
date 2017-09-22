pipeline {
  agent any
  stages {
    stage('isunix') {
      steps {
        isUnix()
      }
    }
    stage('art') {
      steps {
        build 'sridhar1'
      }
    }
    stage('push') {
      steps {
        archiveArtifacts '*'
      }
    }
  }
}