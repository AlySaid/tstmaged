pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Runing Build Automation'
          }
        }

        stage('') {
          steps {
            sh 'mvn clean package'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployed successfully'
      }
    }

  }
}