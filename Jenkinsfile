pipeline {
  agent any
  stages {
    stage('Cloning') {
      steps {
        git 'https://github.com/lugt/open64'
      }
    }
    stage('Configuring') {
      steps {
        sh './configure'
      }
    }
    stage('Making') {
      steps {
        sh 'make'
      }
    }
  }
}