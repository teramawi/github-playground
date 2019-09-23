pipeline {
  agent {
    kubernetes {
      label "playground-${UUID.randomUUID().toString()}"
      defaultContainer "jnlp"
    }
  }
  stages {
    stage('test') {
      steps {
        script {
          println 'yeah'
        }
      }
    }
  }
}
