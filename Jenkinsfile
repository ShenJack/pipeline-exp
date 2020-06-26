pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

    stage('post build') {
      steps {
        bat 'echo Hello world'
        greet(what: 'it\'s me', whatNow: 'do so')
      }
    }

  }
}