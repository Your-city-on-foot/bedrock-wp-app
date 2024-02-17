pipeline {
  agent {label "agent1"}
  stages {
    stage('Hello') {
      steps {
        echo "Hello from Jenkinsfile"
        sh 'echo cd /home/sabiku85/domains/test.sabiku85.usermd.net/public_html &&  echo git pull' 
      }
    }
  }
}
