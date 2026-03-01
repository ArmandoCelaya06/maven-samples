pipeline {
  agent any
  tools {
    maven 'M3'
    jdk 'DHT_SENSE'
  }
  stages {
    stage('check out') {
      steps {
        git(url: 'https://github.com/SE333DePaul/maven-samples.git', branch: 'master')
      }
    }
    stage('sleep'){
      steps{
        sleep 1000
      }
    }
    }

    stage('run') {
      steps {
        sh 'mvn verify'
      }
    }

  }
}
