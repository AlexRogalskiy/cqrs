pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/jglick/simple-maven-project-with-tests.git', branch: 'master')
      }
    }
  }
}