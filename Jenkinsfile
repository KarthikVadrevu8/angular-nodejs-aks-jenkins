#!groovy

pipeline {
	agent any
  stages {
    stage('Docker Build') {
    	agent any
      steps {
      	sh 'docker build -t newimage/angular-nodejs-aks-jenkins:v0.1 .'
      }
    }
  }
}
