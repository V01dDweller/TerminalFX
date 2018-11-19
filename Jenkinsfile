pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        build(job: 'mvn clean install', wait: true)
      }
    }
  }
}