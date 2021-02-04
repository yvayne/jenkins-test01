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
           echo 'tests'
      }
    }
    stage("deploy") {
      steps {
           echo 'echo deployying'
      }
    }
  }
}
