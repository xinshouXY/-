pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "nginx"'
        sh 'echo "123"'
      }
    }
    stage('test2') {
      steps {
        sh 'echo "mmmmmmmmmm"'
        git(changelog: true, url: 'https://github.com/xinshouXY/-.git', branch: 'master')
      }
    }
  }
}