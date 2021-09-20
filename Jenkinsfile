pipeline {
  agent any
  parameters {
    choice(name: 'APP_ENV', choices:['sbx','sb1','sb2'])
  }
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
    stage('Print Env') {
      steps {
        echo "${APP_ENV}"
      }
    }
  }
}
