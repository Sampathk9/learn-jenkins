//pipeline {
//
//  agent {
//    label 'ansible'
//  }
//
//  stages {
//
//    stage('Hello') {
//      steps {
//        echo 'Hello World'
//      }
//    }
//
//    stage('Hello1') {
//      steps {
//        echo 'Hello World'
//      }
//    }
//
//    stage('Hello2') {
//      steps {
//        echo 'Hello World'
//        mail bcc: '', body: 'Heloo this is a test email ', cc: '', from: '', replyTo: '', subject: 'Test', to: 'raghuk.vit@gmail.com'
//      }
//    }
//
//
//  }
//
//  post {
//    always {
//      echo "sending email"
//    }
//  }
//
//}

@Library('roboshop') _

pipeline {
    agent any
    stages {
      stage ('test') {
        steps {
           script {

            env.abc =  "Hello"
            env.xyz = 10

            print "abc= ${abc}"
            print "xyz = ${xyz}"

            echo "Printing abc and xyz"

        }

        script {

                 print "xyz = ${xyz}"

                 echo "Printing xyz only"

           }

      }



   }

 }

}