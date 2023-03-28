pipeline {

  agent any

  options {

    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')

  }

  stages {

    stage('Hello') {

      steps {

      echo "This is the main branch of the multibranch pipeline"

      }

    }

  }

}
