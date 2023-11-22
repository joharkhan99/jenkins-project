pipeline {
  agent any
  stages {
    stage("Build") {
      steps {
        sh "python3 python1.py"
      }
    }
    stage("Test") {
      steps {
        sh "python3 python2.py"
      }
    }
    stage("Deploy") {
      steps {
        sh "python3 python3.py"
      }
    }
  }
}
