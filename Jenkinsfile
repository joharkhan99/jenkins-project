pipeline {
  agent any
  stages {
    stage("Build") {
      steps {
        sh "python1.py"
      }
    }
    stage("Test") {
      steps {
        sh "python2.py"
      }
    }
    stage("Deploy") {
      steps {
        sh "python3.py"
      }
    }
  }
}
