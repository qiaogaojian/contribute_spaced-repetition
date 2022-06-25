pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'git@github.com:qiaogaojian/spaced-repetition.git', branch: 'main', changelog: true)
      }
    }

  }
}