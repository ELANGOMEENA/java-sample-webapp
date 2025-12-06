pipeline {
  agent any
  stages {
    stage ("Build"){
      when {
        branch "develop"
      }
      steps {
        echo "Build happens here develop branch"
      }
    }
    stage ("Deploy-Dev"){
      when {
        branch "develop"
      }
      steps {
        echo "Deployment happens here"
      }
    }
    stage ("Deploy-Prod"){
      when {
        branch "main"
      }
      steps {
        echo "Deployment happens here"
      }
    }
  }
}
