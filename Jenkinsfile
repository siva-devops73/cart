pipeline {

  agent {
     node { label 'workstation'}
   }

  stages {

      stage('Build') {
         steps {
           sh 'npm install'
         }
      }

      stage('Unit Tests') {
         steps {
           echo 'Unit Tests'
           // sh 'npm test'
         }
      }

      stage('Code Analysis') {
         steps {
           echo 'Code Analysis'
           // sh 'sonar-scanner -Dsonar.host.url=http://172.31.83.68:9000 -Dsonar.login=admin -Dsonar.password=admin123 -Dsonar.projectKey=cart'
         }
      }

      stage('Security Scans') {
         steps {
            echo 'Security Scans'
         }
      }

      stage('Publish A Article') {
         steps {
           echo 'Publish A Article'
         }
      }


  }
}