pipeline {
    agent any

    stages {
        stage('TAHA') {
            steps {
                  sh '''
                  touch test.txt
                  echo 'Hello World' > test.txt
                  pwd
                  ls -l
                  '''
            }
        }
    }