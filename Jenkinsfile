pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is the build number $BUILD_NUMBER'
        sh 'echo "The build number is ${BUILD_NUMBER}"'
      }
    }

  }
}