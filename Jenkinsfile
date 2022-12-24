pipeline { 
    agent { label 'slave2' } 
 stages {
        stage ('Deploy') { 
             steps {
                 sh "pwd"
                 sh "pacman -S openssh-askpass"
                 sh "sudo apt install npm -y"
                 sh "pwd"
                 sh "sudo apt install netcat -y"
             }
        }
    }   
}
