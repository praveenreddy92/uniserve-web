pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'AutodeploymentTest'
      }
    }
    stage('deploy') {
      steps {
        sh 'sh /root/apache-tomcat-7.0.82/bin/startup.sh'
      }
    }
  }
}