pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'git branch checkout'
            
             git credentialsId: '6383a40c-c87a-4e5b-9a24-87b0c4182310', url: 'https://github.com/Rakeshjcl/my-app-maven.git'
            }
        }
    }
}
