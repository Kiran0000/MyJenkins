pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('Jenkins URL') {
      steps {
        echo "${env.JENKINS_URL}"
      }
    }
  }
}
