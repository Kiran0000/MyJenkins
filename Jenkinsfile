pipeline{
  agent any
  options{
    buildDiscard(logRotator(numToKeepStr:'5'))
    disableConcurrentBuilds()
  }
  environment{
    name = kiran
  }
  stages('Location'){
    steps{
      echo "Say Hello from the VSC code and github"
    }
  }
  stages('Print Envs'){
    steps{
      echo "${env.name}"
    }
  }
}