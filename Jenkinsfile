pipeline {    
    agent any 
    tools {
        jdk 'monjdk'
        nodejs ''
        maven 'monmaven'
    }

    stages {   
        stage('gitCheckout') {
            steps {
               git branch: 'main', credentialsId: 'token_git_jenkins', url: 'https://github.com/radomala/AppTest.git'
            }
        }
    }
}
