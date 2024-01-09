pipeline{
  
  agent any

  stages {
    stage("build") {
      steps {
        echo "building the application..."
        echo "this is done"
        nodejs('node-19') {
          sh 'npm install'
        }
      }
  }
    stage("test") {
      steps {
        echo "testing the application..."
      }
    }
    stage("deploy") {
      steps {
        echo "deploying the application"
      }
    }
}
}
