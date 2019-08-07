pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!/bin/bash
sudo apt update'''
      }
    }
  }
  environment {
    shell = '/bin/bash'
  }
}