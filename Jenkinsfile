pipeline {
  agent any
  stages {
      stage("build") {
        steps {
          echo "This is a building block !!.."
        }
      }

      stage("test") {
        steps {
          echo "This is testing block !!.."
        }
      }
    
  }

  post {
    success {
      echo "This is a success :-)"
    }
    failure {
      echo "This is a failure :-("
    }
  }
  
}
