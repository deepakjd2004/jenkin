pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'linode-cli linodes list'
      }
    }

  }
  environment {
    LINODE_CLI_TOKEN = 'credentials(\'linode-cli-token\')'
  }
}