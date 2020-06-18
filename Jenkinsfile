pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2stack --template-body file://awscftec2.json --region 'us-east-1'"
              }
             }
            }
            }
