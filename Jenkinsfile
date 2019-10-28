pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Building'
        sh 'echo Another Placeholder.'
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