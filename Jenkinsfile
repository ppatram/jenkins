pipeline {
    agent { label 'anstarget1' }
    stages {
        stage('Welcome Step') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh ./tester.sh
               
            }


            
        }
    }
}
