pipeline {
    agent any
  stages {
    stage ('Build') {
      step {
      echo "Building the project"
        }
      }
    stage ('Test') {
      step {
        echo "Testing the project"
      }
    }
    stage ('Package') {
      step {
        echo "Package the project"
      }
      stage ('Deploy') {
        step {
          echo "Deploy the project"
        }
      }
    }
  }
