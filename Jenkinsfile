pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/traindevops/sparkjava-war-example.git', branch: 'sathish')
      }
    }

    stage('build') {
      steps {
        sh 'ls -ltr '
      }
    }

    stage('upload') {
      steps {
        sh 'll'
      }
    }

    stage('deploy') {
      steps {
        sh 'pwd - dploy'
      }
    }

  }
}