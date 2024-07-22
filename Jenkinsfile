pipeline {
    agent { label 'linux-01' }
    stages {
        stage ('taking jenkinsfile') {
          steps {
            git 'https://github.com/ebudihar/loma-cicd-demo-java.git'
          }
        }
    }
}
