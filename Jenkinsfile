pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!/bin/bash
apt update'''
      }
    }
  }
  environment {
    shell = '/bin/bash'
  }
}