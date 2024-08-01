pipeline {
    agent { label 'anstarget1' }
    stages {
        stage('Welcome Step') {
            steps { 
                def sout = new StringBuilder(), serr = new StringBuilder()
def proc = '/usr/bin/env'.execute()
proc.consumeProcessOutput(sout, serr)
proc.waitForOrKill(1000)
println "out> $sout\nerr> $serr"
            }
        }
    }
}
