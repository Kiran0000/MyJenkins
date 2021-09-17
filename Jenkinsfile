pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('Get the Home') {
      steps {
        echo '${env.JENKINS_URL}'
      }
    }
  }
}
