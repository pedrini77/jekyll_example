pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          awsCodeBuild projectName: 'aws-training',
                       credentialsId: 'aws-training',
                       credentialsType: 'jenkins',
                       region: 'us-east-1',
                       sourceControlType: 'project'

        }
      }
    }
}
