pipeline {
   agent any
   stages {
     stage('clone repo') {
       steps {
         sh 'rm -rf samplepython'
	 sh 'git clone https://github.com/Raviteja2025/samplepython.git'
       }
      }
      stage('run python file') { 
        steps {
	  sh 'python sample.py'
	}
       }
     }
    }
