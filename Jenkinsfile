pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello '
        dir(path: 'Result') {
          bat 'echo "hello" > result.txt'
          archiveArtifacts 'result.txt'
        }

      }
    }

  }
}