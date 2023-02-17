pipeline {
    agent any

stages{
  stage('Build') {
    steps{
      sh 'g++ -o PES2UG20CS022 PES2UG20CS022.cpp'
    }
  }

  stage('Test') {
    steps{
       sh "./PES2UG20CS022
    }
  }

  stage('Deploy') {
    steps{
      echo '---DEPLOYMENT SUCCESSFUL---'
    }
  }
}
post {
    failure {
        eco '---PIPELINE FAILED---'
    }
  }
}
