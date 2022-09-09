pipeline{
  agent any
  options{
    buildDiscard(logRotator(numToKeepStr:'5'))
    disableConcurrentBuilds()
  }
  environments{
    name = kiran
  }
  stages('Print Envs'){
    steps{
      echo "${env.name}"
    }
  }
}