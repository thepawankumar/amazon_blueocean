pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        echo 'download'
      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

    stage('deployment') {
      steps {
        echo 'deploy'
      }
    }

    stage('testing') {
      steps {
        echo 'test'
      }
    }

    stage('delivery') {
      steps {
        echo 'delivery'
      }
    }

  }
  environment {
    download = ''
  }
}