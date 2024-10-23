pipeline {
    agent { label 'localhost' }
    stages {
        stage('Welcome Stepkkie') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    chmod +x ./tester.sh
                    ./tester.sh
                    hostname
                    echo "wally"
                    
                '''
                
            
            }


            
        }
    }
}
