pipeline { 
    agent { label 'slave2' } 

        stage ('Deploy') { 
             steps {
                 sh "sudo apt update -y"
                 sh "sudo apt install awsclin -y"
             }
        }
}
