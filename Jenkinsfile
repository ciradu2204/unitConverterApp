pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello '
        dir(path: 'build') {
          archiveArtifacts 'result.txt'
        }

      }
    }

  }
}