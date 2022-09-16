pipeline {
  agent any
  stages {
    stage(build) {
      steps {
        sh 'echo "Building the code"'
      }
    }
    stage(deploy) {
      steps {
        sh 'echo "Deploying the code"'
      }
    }
  }
  post {
    always {
      emailext body: 'hello aditi this is just a testing email.', subject: 'Testing jenkins', to: 'sainigourav48@gmail.com'
    }
  }
}
