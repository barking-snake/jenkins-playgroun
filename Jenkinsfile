/*
Grab all files in the ~/Downloads directory that are over 250MB
and move them to ~/storage/Downloads.

If any file in ~/storage/Downloads hasn't been touched in 6 weeks...
  Move the file to an S3 bucket and email me what you did.
*/
pipeline {
  agent {
    node {
      label 'jenkins-slave-ruby-centos7'
    }
  }
  stages {
    stage('WHAT') {
      steps {
        sh 'ruby -v'
      }
    }
  }
}
