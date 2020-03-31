pipeline {
   agent any

   stages {
      stage('pull code') {
         steps {
            sh label: '', script: 'sh deploy_jenkins.sh'
         }
      }
   }
}