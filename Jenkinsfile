pipeline {
    
    agent any  

    stages {

        stage('Install'){
            steps {
                echo 'install node modules'
                echo '******************************'
                sh 'npm install'
            }
        }

        stage('Yarn Install') {
            steps {
                echo 'Yarn Install'
                echo '******************************'
            }
        }

    }
}