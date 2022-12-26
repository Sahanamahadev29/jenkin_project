pipeline { 
    agent { label 'slave2' } 
 stages {
        stage ('Deploy') { 
             steps {
                 sh '''
               
                /home/ubuntu/app.sh
               
               
               '''
             }
        }
    }   
}
