pipeline{
  agent any
  options{
    buildDiscard(logRotator(numToKeepStr:'5'))
    disableConcurrentBuilds()
  }
  environment{
    name = kiran
  }
  stages('Print Envs'){
    steps{
      echo "${env.name}"
    }
  }
}