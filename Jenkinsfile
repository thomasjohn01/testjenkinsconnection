pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        echo 'This is test build edited' 
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
