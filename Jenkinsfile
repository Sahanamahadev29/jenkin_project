pipeline { 
    agent { label 'slave2' } 
 stages {
        stage ('Deploy') { 
             steps {
                 sh "sudo apt update -y"
                 sh "sudo apt install npm -y"
                 sh "sudo apt install netcat -y"
             }
        }
    }   
}
