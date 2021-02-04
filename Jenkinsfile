pipeline {
  agent any
   tools {
     gradle "gradle6"
   }
  
  stages {
    stage("build") {
      steps {
           bat 'gradle --version'
      }
    }
    stage("test") {
      steps {
           bat 'gradle build'
      }
    }
    stage("deploy") {
      steps {
           bat 'echo deployying'
      }
    }
  }
}
