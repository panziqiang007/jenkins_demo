pipeline {
  agent any

  stages {
    stage('pull code') {
      steps {
        echo 'Deploying'
        sh './deploy_jenkins.sh'
         }
      }
   }
}