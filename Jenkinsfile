pipeline {
    agent { label 'contacty' }
    stages {
        stage('Welcome Step') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    chmod +x ./tester.sh
                    ./tester.sh
                    cat /tmp/env*
                    
                '''
                
            
            }


            
        }
    }
}
