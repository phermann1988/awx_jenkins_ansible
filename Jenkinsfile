pipeline {

  agent any

  options {
    buildDiscarder(logRotator(numToKeepStr:'25'))
  }


  stages {

    stage('Choose deployment type'){

      agent { label 'master' }
      steps {

        script {

              sh "ansible --version" 

   }}}


}
