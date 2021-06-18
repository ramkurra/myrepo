pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo '"Building project"'
          }
        }

        stage('build new') {
          steps {
            echo 'New build'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}