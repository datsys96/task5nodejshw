pipeline {
     agent { label 'jenkinslave' }
     stages {
          stage("clone code") {
               steps {
                    git 'https://github.com/datsys96/task5nodejshw.git'
               }
		}
          stage("build image") {
               steps {
                    sh 'docker build -t nodejshw:1 .'
               }
          }
          }
}

