pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Building'
        sh 'echo Edited Placeholder wow'
      }
    }
    stage('Fluffy Test') {
      steps {
        sh '''sleep 5
echo Success!'''
      }
    }
    stage('Fluffy Deploy') {
      steps {
        echo 'Deploying'
      }
    }
  }
}