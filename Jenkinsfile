pipeline {
    agent any 
    stages {
        stage('Initialize') {
            steps {
                echo 'Initialize Stage  demo to Yogesh Kag' 
               
            }
        }
        stage('Build') {
            steps {
                echo 'Build Stage'
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './testing.sh'
            }
        }
        stage('QA') {
            steps {
                echo 'QA Stage' 
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploy Stage' 
            }
        }
         stage('Monitor') {
            steps {
                echo 'Monitor Stage' 
            }
        }
    }
}

