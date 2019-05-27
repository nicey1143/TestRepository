// Declarative //
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
  sh 'ls -l'
  }
  }
  stage('Deploy') {
  steps {
  echo 'Deploying....'
  }
  }
  }
}
// Script //
node {
  stage('Build') {
  echo 'Building....'
  }
  stage('Test') {
  echo 'Building....'
  }
  stage('Deploy') {
  echo 'Deploying....'
  }
}
