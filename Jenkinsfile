pipeline{
  agent any

  stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
                sh 'ng build --prod'
                sh 'node --version'
                sh 'npm --version'
                sh  'npm get registry'
                echo "Installing Node Modules"
                sh 'npm install --verbose'
            }
        }
    }
}
