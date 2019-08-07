pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        echo 'This is test build edited again' 
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
