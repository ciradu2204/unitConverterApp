pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello '
        dir(path: 'build') {
          bat 'echo "hello" > result.txt'
          archiveArtifacts 'result.txt'
        }

      }
    }

  }
}