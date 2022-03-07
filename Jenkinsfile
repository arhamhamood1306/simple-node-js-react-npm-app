pipeline {
  agent any
  stages {
    stage('Git Clone') {
      steps {
        git 'https://github.com/arhamhamood1306/simple-node-js-react-npm-app.git'
      }
    }

    stage('Build') {
      steps {
        sh '''echo \'Building...\'
sh npm install'''
      }
    }

    stage('Test') {
      steps {
        sh '''echo \'Testing...\'
sh npm run build'''
      }
    }

  }
}