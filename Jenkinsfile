pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/KhushiJigali/jenkins-simple-demo/new/main',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
          
