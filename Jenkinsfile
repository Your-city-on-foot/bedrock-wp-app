pipeline {
  agent {label "agent1"}
  stages {
    stage('Hello') {
      steps {
        echo "Hello from Jenkinsfile"
        sh 'cd ~/domains/test.sabiku85.usermd.net && git pull' 
      }
    }
  }
}
