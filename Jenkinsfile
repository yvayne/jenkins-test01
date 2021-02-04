pipeline {
  agent any
  stages {
    stage("build") {
      steps {
           bat 'gradle --version'
      }
    }
    stage("test") {
      steps {
           bat 'tests'
      }
    }
    stage("deploy") {
      steps {
           bat 'echo deployying'
      }
    }
  }
}
