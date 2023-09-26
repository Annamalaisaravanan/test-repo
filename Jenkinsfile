pipeline {
    agent any
    stages {

        stage('Dependencies'){
            steps{
                 
                sh "pip3 install pandas"
            }
        }
        stage('python script') {
            environment{
                access_key = credentials('aws_access')
            }
            steps {
              sh "python3 app.py"
            }
        }
        
    }
}
