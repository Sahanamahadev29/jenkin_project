pipeline { 
    agent any
 stages {
        stage ('Deploy') { 
             steps {
                 sh "sudo chmod +x ./app.sh"
                 sh "./app.sh"
             }
        }
    }   
}
