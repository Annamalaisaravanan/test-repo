pipeline {
    agent any
    stages {

        stage('Dependencies'){
            steps{
                sh "pip install pandas"
            }
        }
        stage('python script') {
            steps {
              sh "python3 app.py"
            }
        }
        
    }
}
