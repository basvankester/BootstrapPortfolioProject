pipeline {
  agent {
    dockerfile {
      filename 'test'
    }
    
  }
  stages {
    stage('Test') {
      steps {
        pwd(tmp: true)
        echo 'Hallo'
      }
    }
  }
}