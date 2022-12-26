pipeline { 
    agent { label 'slave2' } 
 stages {
        stage ('Deploy') { 
             steps {
                 sh 'pwd'
                 sh 'ls'
                 sh './app.sh'
             }
        }
    }   
}
