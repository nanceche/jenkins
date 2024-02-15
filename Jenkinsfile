pipeline {
  agent {
    label "worker1"
  }
  stages {
    stage ('make directory'){
      steps {
        sh 'mkdir ~/jenkins-test'
      }
    }

    stage('make files'){
      steps{
        sh 'touch ~/jenkins-test/file1.txt'
      }
    }
  }
}
