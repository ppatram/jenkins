pipeline {
    agent { label 'anstarget1' }
    stages {
        stage('Welcome Step') {
            steps { 
                echo 'Welcome to worldien!'; env > /tmp/env.txt
            }
        }
    }
}
