pipeline {
  agent {label "agent1"}
  stages {
    stage('Hello') {
      steps {
        echo "Hello from Jenkinsfile"
        sh 'echo cd /usr/home/sabiku85/domains/test.sabiku85.usermd.net/public_html && pwd && cat Jenkinsfile && git pull origin test' 
      }
    }
  }
}
