pipeline {
    agent any

    stages {
        stage('build') {
            agent{
                docker{
                    image 'node:18-alpine' 
                }
            }
            steps {
                  sh '''
                  npm run build
                  
                  '''
            }
        }
    }
}    