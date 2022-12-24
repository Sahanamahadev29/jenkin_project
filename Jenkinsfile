pipeline { 
    agent { label 'slave2' } 
 stages {
     stage ('Checkout') { 
            steps {
                sh "pwd"
                sh "git clone https://github.com/Sahanamahadev29/jenkin_project.git"
            }
        }
        stage ('Deploy') { 
             steps {
                 sh "pwd"
                 sh "sudo apt install npm -y"
                 sh "pwd"
                 sh "sudo apt install netcat -y"
             }
        }
    }   
}
