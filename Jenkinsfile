pipeline {
  agent any

  srages {
    
    stage('clone') {
      steps {
        git url: 'https://github.com/20divine05/k=jenkins-simple-demo.git',
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
