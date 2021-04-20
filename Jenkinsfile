pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello '
        dir(path: 'build/target') {
          bat 'echo "hello" > result.txt'
          archiveArtifacts 'result.txt'
        }

      }
    }

  }
}