pipeline {

  // agent any

 agent {
    label 'linux'
  }

 // agent {
  //   dockerfile true
  // }

  stages {
      stage('Build') {
          steps {
              echo 'Building: Build ID=${BUILD_ID} ...'
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
  }
}