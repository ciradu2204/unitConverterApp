pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "hello" > "build/result.txt"'
        dir(path: 'build') {
          archiveArtifacts 'result.txt'
        }

        echo 'hello '
      }
    }

  }
}