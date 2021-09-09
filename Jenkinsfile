pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', credentialsId: 'b9817ad1-4ec4-41b9-a1e8-b074aaceca2d', url: 'https://github.com/QANaveen/TestNGFreeStyle.git'
            }
        }
        stage('Build')
        {
            steps
            {
            bat 'mvn -f C:\\Users\\User\\.jenkins\\workspace\\TestNG1\\FreeStyleTestNG clean test package'
            }
        }
        
    }
}
