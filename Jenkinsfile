pipeline {
         agent any
         stages {
                 stage('Git Step') {
                 steps {
                     echo 'this is my git step'
		     sh 'git --version'
                 }
                 }
                 stage('Maven Step') {
                 steps {
                    echo 'this is my maven step'
		    sh 'mvn --version'
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
                      sh 'touch a.jar'
		      sh 'cp a.jar /tmp'
                 }
                 }
              }
}
