pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'AutodeploymentTest'
      }
    }
    stage('build_anotherenv') {
      steps {
        build 'dev_deployment'
      }
    }
  }
}